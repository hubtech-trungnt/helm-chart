# Project structure


`<namespace>`

    `<component>`

    `	<chart>`

├── README.md
├── argocd
│   └── argocd
│       ├── Chart.yaml
│       ├── charts
│       │   └── argo-cd-5.51.6.tgz
│       ├── debug.yaml
│       ├── templates
│       │   ├── argocd-application.yaml
│       │   ├── cert-manager-application.yaml
│       │   └── project.yaml
│       └── values.yaml
├── cert-manager
│   └── cert-manager
│       ├── Chart.yaml
│       ├── templates
│       │   └── issuer.yaml
│       └── values.yaml
└── ingress-nginx
    └── ingress-nginx

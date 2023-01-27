# kustomize-base

├── base
│   ├── kustomization.yaml
│   ├── redis
│   │   ├── deployment.yaml
│   │   ├── kustomization.yaml
│   │   └── service.yaml
│   ├── backend
│   │   ├── configmap.yaml
│   │   ├── deployment.yaml
│   │   ├── kustomization.yaml
│   │   ├── secrets.yaml
│   │   └── service.yaml
│   ├── frontend
│   │   ├── configmap.yaml
│   │   ├── deployment.yaml
│   │   ├── kustomization.yaml
│   │   └── service.yaml
│   ├── namespace.yaml
│   ├── secrets.yaml
│   └── virtualservice.yaml
├── overlays
│   └── dev
│       ├── configmap-backend.yaml
│       ├── configmap-frontend.yaml
│       ├── kustomization.yaml
│       ├── backend-env.yaml
│       ├── backend-secrets.yaml
│       └── virtualservice.yaml
│   └── qa
│       ├── configmap-backend.yaml
│       ├── configmap-frontend.yaml
│       ├── kustomization.yaml
│       ├── backend-env.yaml
│       ├── backend-secrets.yaml
│       └── virtualservice.yaml
│   └── prod
│       ├── configmap-backend.yaml
│       ├── configmap-frontend.yaml
│       ├── kustomization.yaml
│       ├── backend-env.yaml
│       ├── backend-secrets.yaml
│       └── virtualservice.yaml
└── README.md

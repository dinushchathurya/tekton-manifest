tekton-node-app
├── base
│   ├── deployment.yaml
│   ├── kustomization.yaml
│   ├── ingress.yaml
│   └── service.yaml
└── overlays
    ├── dev
    │   ├── kustomization.yaml
    │   └── deployment-patch.yaml
    └── qa
        ├── kustomization.yaml
        └── deployment-patch.yaml
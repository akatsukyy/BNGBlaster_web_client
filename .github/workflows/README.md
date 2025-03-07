# Workflow tree

## Wỏkflow-1: Build,test BNGBLASTER App and update chart, helm_chart version
Job1: 
`- Checkout code`
`- Build and push image with tag "cache" to ghcr`
Job2: 
`- Pull image and run container`
`- Robot test`
## Workflow-2: Scan Dockerfile and Image

    
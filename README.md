# Sourish Private Helm Repository
Private Helm Chart Repository Hosted on GitPages - by Sourish Bhattacharya

### Create new helm chart
- helm package <chart-name> -d charts/
- helm repo index charts

### Publish chart
- git add .
- git commit -m "commit message"
- git push origin main
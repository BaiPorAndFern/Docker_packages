# Full_Stack
# Push a image into Github Packages (GHCR)
1. Create image
2. Create Personal Access Token (PAT) on Github
3. Authenticate GHCR (Github Container Registry)
'''
export CR_PAT=<TOKEN>
echo $CR_PAT | docker login ghcr.io -u USERNAME --password-stdin
'''

4. Tag and push out image to GHCR




# Use Github Actions to Publish a Docker image to Github Packages (GHCR)
<!-- fetched 2026-10-13 from https://learn.microsoft.com/en-us/azure/container-registry/container-registry-image-formats by sweep-shape-compat.py; text extracted from the provider's own page -->

Supported Content Formats by ACR, Docker, OCI, and Helm - Azure Container Registry | Microsoft Learn Skip to main content Skip to Ask Learn chat experience 
 This browser is no longer supported.
 Upgrade to Microsoft Edge to take advantage of the latest features, security updates, and technical support. 
 Download Microsoft Edge More info about Internet Explorer and Microsoft Edge 
 Table of contents Exit editor mode 
 Ask Learn Ask Learn Reading mode Table of contents Read in English Add Add to Plans Edit Copy Markdown Print 
 Note 
 Access to this page requires authorization. You can try signing in or changing directories . 
 Access to this page requires authorization. You can try changing directories . 
 Content formats supported in Azure Container Registry
 Feedback 
 Summarize this article for me 
 In this article 
 Use a private repository in Azure Container Registry to manage one of the following content formats.
 Docker-compatible container images
 The following Docker container image formats are supported:
 Docker Image Manifest V2, Schema 1 
 Docker Image Manifest V2, Schema 2 - includes Manifest Lists which allow registries to store multi-architecture images under a single image:tag reference
 OCI images
 Azure Container Registry supports images that meet the Open Container Initiative (OCI) Image Format Specification , including the optional image index specification. Packaging formats include Singularity Image Format (SIF) .
 OCI artifacts
 Azure Container Registry supports the OCI Distribution Specification , a vendor-neutral, cloud-agnostic spec to store, share, secure, and deploy container images and other content types (artifacts). The specification allows a registry to store a wide range of artifacts in addition to container images. You use tooling appropriate to the artifact to push and pull artifacts. For examples, see:
 Push and pull an OCI artifact using an Azure container registry 
 Push and pull Helm charts to an Azure container registry 
 To learn more about OCI artifacts, see the OCI Registry as Storage (ORAS) repo and the OCI Artifacts repo on GitHub.
 Helm charts
 Azure Container Registry can host repositories for Helm charts , a packaging format used to quickly manage and deploy applications for Kubernetes. Helm client version 3 is recommended. See Push and pull Helm charts to an Azure container registry .
 Next steps
 See how to push and pull images with Azure Container Registry.
 Use ACR tasks to build and test container images.
 Use the Moby BuildKit to build and package containers in OCI format.
 Set up a Helm repository hosted in Azure Container Registry.
 Feedback
 Was this page helpful? 
 Yes No No Need help with this topic? 
 Want to try using Ask Learn to clarify or guide you through this topic? 
 Ask Learn Ask Learn 
 Suggest a fix? 
 Additional resources 
 Last updated on 2024-09-19 
 In this article
 Was this page helpful? 
 Need help with this topic? 
 Want to try using Ask Learn to clarify or guide you through this topic? 
 Ask Learn Ask Learn 
 Suggest a fix? 
 en-us Your Privacy Choices 
 Theme Light 
 Dark 
 High contrast 
 AI Disclaimer 
 Previous Versions 
 Blog 
 Contribute 
 Privacy 
 Consumer Health Privacy 
 Terms of Use 
 Trademarks 
 © Microsoft 2026

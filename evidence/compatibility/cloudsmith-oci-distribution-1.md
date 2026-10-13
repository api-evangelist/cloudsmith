<!-- fetched 2026-10-13 from https://help.cloudsmith.io/docs/docker-registry by sweep-shape-compat.py; text extracted from the provider's own page -->

Docker registry | Cloudsmith Docs 
 Documentation 
 Search 
 Search Book a demo Login 
 Documentation Guides API reference 
 Docker About Cloudsmith 
 Key concepts 
 Common use cases 
 Sign up 
 Log in 
 Supported formats 
 Alpine 
 Cargo 
 Chocolatey 
 Cocoapods 
 Composer 
 Conan 
 Conda 
 CRAN 
 Dart 
 Debian 
 Docker 
 Generic 
 Go 
 Hugging Face 
 Gradle 
 Helm 
 Hex 
 LuaRocks 
 Maven 
 Nix 
 npm 
 NuGet feed 
 NuGet symbol server 
 OCI 
 PowerShell modules 
 Python 
 Raw 
 RedHat 
 Ruby 
 sbt 
 Swift 
 Signing Swift packages 
 Terraform 
 Unity 
 Vagrant 
 Workspaces 
 Create a workspace 
 Workspace overview 
 Settings 
 Privileges 
 Personalization 
 Authentication 
 SAML 
 SSO with Microsoft Entra ID 
 SSO with Google 
 SSO with JumpCloud 
 SSO with PingIdentity 
 SSO with Okta 
 SSO with OneLogin 
 SCIM 
 2FA 
 OpenID Connect 
 GitHub Actions 
 Jenkins 
 Dynamic OIDC Mapping 
 Custom domains 
 API key rules 
 Repositories 
 Create a repository 
 Settings 
 Custom storage regions 
 Upstreams 
 Upstream proxy agent 
 Connected repositories 
 Privileges 
 Geo/IP rules 
 Teams and accounts 
 Teams 
 Member accounts 
 API keys 
 Service accounts 
 Privileges 
 Artifact management 
 Package actions 
 Package upload 
 Package download 
 Package identification 
 Copy a package 
 Package move 
 Delete a package 
 Package resynchronization 
 Package tags 
 Private package sharing 
 Package search syntax 
 Retention rules 
 Package groups 
 Troubleshooting 
 Recently deleted packages 
 Custom metadata 
 Via the API 
 Via the CLI 
 Via the web app 
 Supply chain security 
 Package signing 
 SBOMs 
 Risk detection 
 License detection 
 Malware scanning 
 Malicious package detection 
 Vulnerability detection 
 Vulnerability scanning 
 GitHub secret scanning 
 Package quarantine 
 Block until scan 
 Policy management 
 Policy as code 
 Create a policy as code 
 Policy exemptions 
 Rego recipes 
 Policy as code workflow example 
 Cooldown policy 
 Vulnerability policy 
 License policy 
 Package deny policy 
 Upstream trust 
 Observability and logs 
 Client logs 
 Audit logs 
 Package logs 
 Policy decision logs 
 Usage 
 Exporting logs to Azure 
 Exporting logs to S3 
 Analyzing logs with Athena 
 Software distribution 
 Broadcasts 
 Customization 
 Private broadcasts 
 Entitlement tokens 
 Via the API 
 Via the CLI 
 Via web app 
 EULA enforcement 
 Integrations 
 Aikido 
 Ansible 
 ArgoCD 
 AWS CodeBuild 
 AWS SageMaker 
 Azure DevOps 
 Bitbucket Pipelines 
 Buildkite 
 Chainguard Containers 
 Chainguard Libraries 
 Chef 
 CircleCI 
 Codefresh 
 Cursor IDE 
 Datadog 
 Dependabot 
 Docker Hardened Images 
 Docker Hub 
 Drone CI 
 GCP CloudBuild 
 GitHub Actions 
 GitLab CI/CD 
 Harness CD 
 Jenkins 
 MCP 
 Microsoft Teams 
 MLflow 
 Octopus Deploy 
 Postman 
 Puppet 
 RapidFort Curated Images 
 RapidFort Curated Libraries 
 Roadie 
 Renovate 
 Semaphore CI 
 Slack 
 Terraform provider 
 TeamCity 
 Theia IDE 
 Travis CI 
 VS Code extension 
 WizOS 
 Zapier 
 Developer tools 
 Generating an API key 
 Cloudsmith CLI 
 API reference 
 VS Code extension 
 API bindings 
 Webhooks 
 Terraform provider 
 Developer community 
 Migrating to Cloudsmith 
 Migration phases 
 Phase 1: Initiation 
 Phase 2: Planning 
 Phase 3: Artifact migration 
 Migrating artifacts from JFrog Artifactory 
 Migrating artifacts from Sonatype Nexus 
 Configuring legacy platforms as upstreams 
 Running a bulk import 
 Importing packages with the CLI 
 Importing Docker images 
 Phase 4: Validation 
 Migration case studies 
 Migration support 
 Resources 
 Contact us 
 Bug bounty program 
 Open source policy 
 Troubleshooting 
 Contributing 
 Contributor License Agreement 
 Support 
 Enterprise Support 
 Billing 
 Service level agreement 
 Operational performance 
 Security at Cloudsmith 
 Security policy 
 Data security posture management 
 Supported formats
 Docker registry 
 Cloudsmith provides public & private registries for Docker images.
 OCI Support
 Cloudsmith provides public & private registries for OCI artifacts, to learn more about it visit our OCI Repository documentation.
 Hardened Image Support
 Cloudsmith provides support for upstreams to Chainguard Containers, Docker Hardened Images, and WizOS registries. For more information about configuring upstreams for these registries, see:
 Integrating with Chainguard Containers 
 Integrating with Docker Hardened Images 
 Integrating with WizOS 
 This list is not comprehensive. Please refer to the upstream sources for more information.
 Docker is an ecosystem used to run packaged software known as containers. A container image is bundled with all of the software and configured to run as an independent process (or collection of processes), and an executing container is isolated from other containers and processes.
 Docker provides the concept of the registry as an artifact data service for storing and distributing image containers. The official one of which is Docker Hub , which is owned and operated by Docker itself.
 Cloudsmith provides a fully fledged Docker registry that is fully compatible with current and future versions of the Docker engine and container image formats. With Cloudsmith, you can push, pull, inspect, and manage container images privately and publicly.
 This is provided with the standard functionality and features offered in the Cloudsmith platform, such as collaboration, advanced permissions, white-labeled distribution, multi-tenancy with other packaging formats, etc.
 For more information on Docker, please see:
 Docker : The official website for Docker (the company and product).
 Docker Hub : The official public registry for Docker repositories.
 Docker Article : The Wikipedia article on Docker.
 Storage Deduplication
 Cloudsmith's Docker repositories benefit from native Docker image layer storage deduplication technology. This means that if you upload several images sharing some of their composing layers, those layers will be reused. This reduce the amount of artifact data and package delivery required to distribute the images across all repositories within a workspace.
 Differences from Docker 
 For clarity, it's important to note some of the differences between a registry such as Docker Hub, and a Cloudsmith Docker registry. These are both naming and functional in nature.
 Naming differences 
 Docker defines the following names (this is not the official wording):
 Layer : A blob (big object of bytes) containing software and configuration.
 Image : A collection of Docker layers plus metadata that represent an application.
 Container : A running instance of a Docker image in-memory.
 Repository : A collection of Docker images, separated by hashref and version tags.
 Registry : A collection of all Docker repositories, separated by namespaces.
 For comparison purposes, where terms differ from Cloudsmith:
 Package : A specific identifiable and versionable artifact.
 Repository : A collection of versionable artifacts, with multiple allowed per account.
 Therefore, based on the above, the following terms are equivalent:
 Docker Term | Cloudsmith Term | 
 Image | Package | 
 Registry | Repository | 
 For consistency, the Docker terms will be used within all of the Docker-related documentation but please be aware of the differences if looking at documentation elsewhere.
 Functionality differences 
 We have attempted to achieve absolute compatibility at the wire (API) level with Docker Hub and the Docker registration specification (2.0) . The functionality differs in how the registry itself is treated.
 Referring to the naming differences section above, every Cloudsmith account can have multiple Cloudsmith repositories. Each Cloudsmith repository is an individual Docker registry in its own right and will require a different login in order to push/pull images for it.
 As such, it is also not possible to have a global registry of all images on Cloudsmith. This may change in the future as we introduce different forms of Cloudsmith repositories and groupings.
 Contextual Documentation
 The examples in this document are generic. Cloudsmith provides contextual setup instructions within each repository, complete with copy and paste snippets (with your namespace/repo/rsa-key pre-configured).
 In the following examples:
 Identifier | Description | 
 OWNER | Your Cloudsmith account name or organisation name (namespace) | 
 REGISTRY | Your Cloudsmith Repository name (also called "slug") | 
 TOKEN | Your Cloudsmith Entitlement Token (see Entitlements for more details) | 
 USERNAME | Your Cloudsmith username | 
 PASSWORD | Your Cloudsmith password | 
 API-KEY | Your Cloudsmith API Key | 
 IMAGE_NAME | The name of your Docker image | 
 TAG | A tag for your Docker image | 
 Upload an image 
 Custom Domains
 If you have added a Custom Domain for Docker, you must use it to authenticate and push. Please replace docker.cloudsmith.io in the following instructions with the Docker custom domain you have created.
 Publish via Docker 
 The endpoint for the native Docker API is:
 https://docker.cloudsmith.io/v2/OWNER/REGISTRY/ 
 Or if you're referring to it from docker commands:
 docker.cloudsmith.io/OWNER/REGISTRY 
 In order to authenticate for native publishing, you'll need use docker login :
 shell
 docker login docker.cloudsmith.io 
 You will be prompted for your Username and Password. Enter your Cloudsmith username and your Cloudsmith API Key.
 To publish an image to a Cloudsmith-based Docker registry, you first need to tag your image:
 shell
 docker tag IMAGE_NAME:TAG docker.cloudsmith.io/OWNER/REGISTRY/IMAGE_NAME:TAG 
 About 'latest' tags
 Docker images are not automatically tagged as 'latest' based on upload date / time. In order to ensure that you have an image tagged as 'latest' you need to explicitly tag the image. For example:
 shell
 docker tag your-image:latest docker.cloudsmith.io/org/repo/your-image:latest 
 You can then publish the tagged image using docker push :
 shell
 docker push docker.cloudsmith.io/OWNER/REGISTRY/IMAGE_NAME:TAG 
 Upload via the Cloudsmith CLI or website 
 To upload via the Cloudsmith CLI or Website. you need to export your Docker image first. You can do this with:
 shell
 docker save -o IMAGE_NAME.docker IMAGE_NAME:TAG 
 This exports the full contents of the image, including all metadata and layers.
 Upload via Cloudsmith CLI 
 For full details of how to install and setup the Cloudsmith CLI, see Command Line Interface .
 The command to upload a Docker image via the Cloudsmith CLI is:
 shell
 cloudsmith push docker OWNER/REGISTRY IMAGE_NAME.docker 
 Example:
 shell
 cloudsmith push docker org/repo your-image.docker 
 Upload via Cloudsmith web app 
 Please see Upload a Package for details of how to upload via the Cloudsmith web app .
 Download / pull an image 
 Setup 
 Public registries 
 For public registries, no further setup is needed as authentication is not required.
 Private registries 
 Private Repositories
 Private Registries require authentication. You can choose between three types of authentication, Entitlement Token Authentication, Service Token Authentication or HTTP Basic Authentication. The setup method will differ depending on what authentication type you choose to use.
 Warning
 Entitlement Tokens, Service Tokens, User Credentials and API-Keys should be treated as secrets, and you should ensure that you do not commit them in configurations files along with source code, or expose them in any logs.
 You need to authenticate via docker login to pull images:
 shell
 # Entitlement Token Auth docker login docker.cloudsmith.io Username: OWNER/REGISTRY Password: TOKEN Login Succeeded 
 shell
 # Service Token Auth docker login docker.cloudsmith.io Username: SERVICE_NAME Password: TOKEN Login Succeeded 
 shell
 # HTTP Basic Auth (User & Pass) docker login docker.cloudsmith.io Username: OWNER/REGISTRY Password: PASSWORD Login Succeeded 
 shell
 # HTTP Basic Auth (API-Key) docker login docker.cloudsmith.io Username: OWNER/REGISTRY Password: API-KEY Login Succeeded 
 shell
 # HTTP Basic Auth (Token) docker login docker.cloudsmith.io Username: OWNER/REGISTRY Password: TOKEN Login Succeeded 
 Pull an image 
 Pulling (downloading) an image from the Cloudsmith Docker registry can be done using the standard docker pull command:
 shell
 docker pull docker.cloudsmith.io/OWNER/REGISTRY/IMAGE_NAME:TAG 
 To refer to this image after pulling in a Dockerfile, specify the following:
 FROM docker.cloudsmith.io/OWNER/REGISTRY/IMAGE_NAME:TAG 
 Security scanning 
 Supported Please see our Security Scanning documentation for further information.
 Current limitations 
 The Cloudsmith Docker registry implementation has the following limitations:
 Remote layer mounting (for non-distributable layers, such as Windows) is not supported.
 Digests for images will not match those pushed to Docker Hub (but layers will match).
 Digests for offline image uploads (via docker save ) will not match those from docker push .
 Upstream proxying / caching 
 Configurable Proxying Caching You can configure upstream Docker registries you wish to use for images. In addition, you can also choose to cache any requested images for future use.
 Refreshing cached images from upstream
 By default, Cloudsmith does not re-pull an image from an upstream once it has been cached. If the latest tag is updated upstream, Cloudsmith continues to serve the cached version.
 To allow pulls to fetch and cache newer versions of an already-cached image, contact Support to enable this feature.
 Sources 
 Cloudsmith supports Docker v2-compliant registries as upstream sources. The table below lists registries that have been officially tested and confirmed. Other registries might work, but are not officially tested.
 Registry | Default upstream URL | Provider | Auth required | 
 Amazon ECR (Private) | https://ACCOUNT.dkr.ecr.REGION.amazonaws.com | Amazon Web Services | ✅ | 
 Amazon ECR (Public) | https://public.ecr.aws | Amazon Web Services | | 
 Azure Container Registry | https://REGISTRY.azurecr.io | Microsoft Azure | ✅ | 
 Chainguard | https://cgr.dev | Chainguard | ✅ | 
 Docker Hardened Images (DHI) | https://dhi.io | Docker, Inc. | | 
 Docker Hub | https://index.docker.io | Docker, Inc. | | 
 GitLab Container Registry | https://registry.gitlab.com | GitLab | ✅ | 
 Google Artifact Registry | https://REGION-docker.pkg.dev | Google Cloud | ✅ | 
 Google Container Registry | https://gcr.io | Google Cloud | ✅ | 
 Harbor | https://HOSTNAME | CNCF / Self-hosted | ✅ | 
 JFrog Artifactory | https://INSTANCE.jfrog.io | JFrog | ✅ | 
 Kubernetes Registry | https://registry.k8s.io | CNCF / Kubernetes | | 
 Microsoft Artifact Registry | https://mcr.microsoft.com | Microsoft | | 
 Minimus (Community Edition) | https://reg.mini.dev | Minimus | | 
 NVIDIA NGC | https://nvcr.io | NVIDIA | ✅ | 
 Quay.io | https://quay.io | Red Hat | | 
 Sonatype Nexus | https://HOSTNAME/repository/REPO-NAME | Sonatype | ✅ | 
 Wiz Registry (Private) | https://registry.wiz.io | Wiz | ✅ | 
 Wiz Registry (Public) | https://wiziopublic.azurecr.io | Wiz | | 
 WizOS | https://registry.os.wiz.io | Wiz | ✅ | 
 Docker Hub and DHI upstream authentication
 If no authentication credentials are provided for a Docker Hub or DHI upstream, it will authenticate by using a Cloudsmith-managed Organization Access Token (OAT). This gives you a higher rate limit than fully anonymous access. 
Your workspace name will be shared with Docker so that they can attribute usage to the originating workspace.
 Warning
 If you have a Docker upstream configured, please be aware of the following behaviors observed when making requests against the Docker API v2 endpoints:
 Tags/List : All tags from the upstream are returned, not just local Cloudsmith tags.
 Manifests : This will trigger a cache of the referenced image to your Cloudsmith repository.
 Iterating through a list of tags to fetch manifests will trigger automatic caching for every image. This can result in hundreds or thousands of cached images, significantly increasing artifact storage consumption and associated costs.
 Key signing support 
 RSA Index Troubleshooting 
 Please see the Troubleshooting page for further help and information.
 Updated 5 days ago 
 Updated 5 days ago
 Made with by Cloudsmith © 2026 
 Docs Guides API Reference Terms & Privacy Contact

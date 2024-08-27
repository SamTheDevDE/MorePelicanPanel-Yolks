# Docker Images for Pelican Panel

> [!WARNING]
> THIS REPO IS STILL UNDER CONSTRUCTION AND THEREFOR LINKS LIKE THE `ghcr.io/...` LINK ARE ONLY TEMPORARY OR TEMPLATES AND NOT THE ACTUAL IMAGES IF YOU WANT THE IMAGES HELP ME HOST THEM ON `ghcr.io` OR ELSE WAIT

> [!NOTE]
Docker images are not yet hosted on `ghcr.io` and i would be thankful if someone helped me to host them there! they will be in categorys such as `nodejs` or other languages like `python` or `java`.

### Heres a list of all in the repository available Docker images

* **NodeJS** — contains images for different Node.js versions with preinstalled npm packages like canvas or canvacord, designed for running applications requiring canvas or canvacord in an Pelican panel.

## Contributing

To add a new version of Node.js or any other language, you would place the docker file in thei're respective directory as example `nodejs/20` or `java/17` etc. Update the `.github/workflows` file to ensure that the new version is tagged correctly.

## Available Images

### [Node.js](/NodeJS)

* [`Node12`](/NodeJS/12.22.12/)
  * `ghcr.io/myusername/nodejs:12`
* [`Node18`](/NodeJS/18.20.4/)
  * `ghcr.io/myusername/nodejs:18`

## Usage

1. **Pull the Docker Image**

    Pull the Docker image using:

    `docker pull ghcr.io/myusername/nodejs:12`

2. **Run the Docker Container**

    Start the container with:

    `docker run -d --name my-node-app -p 3000:3000 ghcr.io/myusername/nodejs:12`

3. **Integrate it into ur Pelican Panel**

    * look at my other .
    * Set environment variables and other configurations as needed.

## Support

For issues or questions, please open an issue on our [GitHub repository](https://github.com/SamTheDevDE/MorePelicanPanel-Yolks/issues).

Thank you for using our Docker image! Happy coding! 🚀

---

FROM gcr.io/forgerock-io/ig/pit1:7.1.0-cbc926d886bd22732687388be83ed5790d31f49f

# Copy all config files into the docker image.
# The default ig directory is /var/ig, and it expects subfolders config/ and scripts/ (if required)
COPY --chown=forgerock:root . /var/ig

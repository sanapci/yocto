# Setup

Initialize build folder with the following command to use configuration files from custom layer:

`$ TEMPLATECONF=meta-cubietruck_plus/conf/templates/default . poky/oe-init-build-env build-try-default`

# Build

`$ bitbake core-image-minimal`
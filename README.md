## Link files generation

ls | sort | xargs -i echo /opt/zephyr-sdk/bin/{} /usr/bin/{}

## GCC version

Versions less than 12 fail to compile due to new Ada lang syntax in GNAT sources

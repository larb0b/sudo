FROM docker.io/library/debian:testing

RUN DEBIAN_FRONTEND=noninteractive TZ=America/Denver apt-get update && \
    DEBIAN_FRONTEND=noninteractive TZ=America/Denver apt-get install -y \
	build-essential curl dpkg-dev ed libldap2-dev libpam0g-dev \
	libsasl2-dev libselinux1-dev libsepol1-dev libssl-dev zlib1g-dev \
	libaudit-dev libssl-dev python3-dev libpython3-dev \
	file lsb-release fakeroot procps git ssh openssh-client
RUN useradd -ms /bin/bash build

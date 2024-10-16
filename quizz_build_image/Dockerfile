FROM openclassrooms/build_image

RUN  sed -i '6d' /etc/apt/sources.list \
&& sed -i '4d' /etc/apt/sources.list \
&& sed -i 's/deb.debian.org/archive.debian.org/g' /etc/apt/sources.list \
&& apt-get update -yq \
&& apt-get install nginx -yq

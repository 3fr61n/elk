FROM elasticsearch:latest



RUN \
	apt-get -y update && apt-get -y --no-install-recommends install \
		wget \
		curl \
		python-pip \
		python-dev \
		python-yaml 

RUN pip install elasticsearch-curator
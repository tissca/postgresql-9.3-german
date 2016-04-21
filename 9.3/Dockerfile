FROM postgres:9.3

RUN  sed -ri 's/#(.*de_DE.*)$/\1/' /etc/locale.gen \
 	&& sed -ri 's/#(.*en_US.*)$/\1/' /etc/locale.gen \
	&& locale-gen


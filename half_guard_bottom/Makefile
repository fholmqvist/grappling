SHELL := /bin/bash

images:
	mv ~/*.jpg .
	for f in celluloid-shot*.jpg; do \
		num=$$(echo $$f | sed -E 's/celluloid-shot0*([0-9]+)\.jpg/\1/'); \
		mv $$f $$(printf "%03d.jpg" $$num); \
	done

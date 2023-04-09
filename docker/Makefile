Dockerfile: Dockerfile.gen
	cp $< $@

Dockerfile.gen: create_dockerfile_and_build.py
	python create_dockerfile_and_build.py \
		--triton-version 22.12 \
		--dry-run


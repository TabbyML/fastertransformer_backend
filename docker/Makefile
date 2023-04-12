build: Dockerfile
	docker build \
		-t tabbyml/fastertransformer_backend:latest \
		-f $< \
		..

build_aptdeps: Dockerfile
	docker build --target aptdeps \
		-t tabbyml/fastertransformer_backend:aptdeps \
		-f $< \
		..

build_pytorch: Dockerfile
	docker build --target pytorch \
		-t tabbyml/fastertransformer_backend:pytorch \
		-f $< \
		..

build_backend: Dockerfile
	docker build --target backend \
		-t tabbyml/fastertransformer_backend:backend \
		-f $< \
		..

build_final: Dockerfile
	docker build --target final \
		-t tabbyml/fastertransformer_backend:final \
		-f $< \
		..

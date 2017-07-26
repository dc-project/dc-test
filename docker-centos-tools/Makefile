all: build

build:
	@docker build --tag=nvwa/ctools:latest .
	@docker push nvwa/ctools:latest

release: build
	@docker build --tag=nvwa/ctools:$(shell cat VERSION) .
	@docker push nvwa/ctools:$(shell cat VERSION)
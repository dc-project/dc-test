all: build

build:
	@docker build --tag=nvwa/ctools:latest .

release: build
	@docker build --tag=nvwa/ctools:$(shell cat VERSION) .
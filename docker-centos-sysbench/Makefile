all: build

build:
	@docker build --tag=nvwa/sysbench:latest .

release: build
	@docker build --tag=nvwa/sysbench:$(shell cat VERSION) .
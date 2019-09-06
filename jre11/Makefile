.PHONY: all
all: flink-jre8 flink-jre11

.PHONY: flink-%
flink-%:
	docker build -t $@ -f Dockerfile-$@ .

include ../make.default

COMPONENT=josdemo

info:
	@echo "${COMPONENT} Component"

prune:
	${CCMD} image prune -f

play:
	${CCMD} play kube josdemo.yaml

down:
	${CCMD} play kube --down josdemo.yaml

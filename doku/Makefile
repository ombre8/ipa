.PHONY: all
	all:   inputs.tex

inputs.tex: $(wildcard dir/*.tex)
	  ls -v journal/*.tex | awk '{printf "\\input{%s}\n", $$1}' > inputs.tex

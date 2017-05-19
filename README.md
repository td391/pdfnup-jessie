# Docker for pdfnup from jessie

## Run
```
docker run -it --rm -v "$(pwd):/src" pdfnup-jessie --nup 2x1 --suffix '2x1' --batch /src/input.pdf --outfile /src
```

## Build
```
docker build -t pdfnup-jessie .
```

## Ref
http://www2.warwick.ac.uk/fac/sci/statistics/staff/academic-research/firth/software/pdfjam

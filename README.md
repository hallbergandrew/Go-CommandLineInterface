# Go-CommandLineInterface

## Can use the command line to find JSON from CSV


CREATE FILE: ${HOME}/famous-gophers.csv

      INSIDE FILE(famous-gophers.csv): 
        Mac, 1947, The Goofy Gophers
        Tosh, 1947, The Goofy Gophers
        Samuel J. Gopher, 1966, Winnie the Pooh
        Chief Running Board, 1968, Go Go Gophers
        Ruffled Feathers, 1968, Go Go Gophers

BUILD: go build -o csv2json .

RUN: ./csv2json -infile ${HOME}/famous-gophers.csv

REFERENCE: https://github.com/kelseyhightower/intro-to-go-workshop/blob/master/labs/docs/csv2json_cli.md

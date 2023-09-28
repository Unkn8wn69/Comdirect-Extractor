# Comdirect-Extractor
Scripts to extract data from Comdirect CSV exports


## Goal
The goal of this project is to give Comdirect users a chance to analyse their Banking statements and get statstics on them. Furthermore this project should also encourage Comdirect to implement similar functions into their (web) apps to help with the user experience.

## Roadmap
- [ ] Export scripts
  - [ ] Income, Expenses and Revenue
  - [ ] Paisa Converter
  - [ ] Graphs

## Structure.
Every script should take the sample from the file data.csv which should contain multiple accounts, a depot and a bunch of transactions. 
If a script generates any outputs they should be saved into outputs/{script_name}_export

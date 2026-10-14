# Optimizing Fire Station Locations: Balancing Service Coverage and Accessibility in the London Borough of Hillingdon

This project presents a bi-objective spatial optimisation of fire station locations in the London Borough of Hillingdon, jointly considering service coverage and accessibility.

## Structure

This project consists of four parts. The full and detailed description of the project is in `manuscript.docx`; and `code.ipynb` is the implementation. The data required by the code notebook are stored in `data/`, and its key visual outputs are saved in `figure/`.

```
├── manuscript.docx     
├── code.ipynb          
├── data/               
│   ├── borough/        # London borough boundaries
│   ├── current_station/ # existing fire stations
│   ├── fire_incident/  # cleaned incident records
│   ├── oa/             # demand areas
│   └── msoa/           # new candidate stations
└── figure/             
```

## How to run

Open `code.ipynb` from the project root and run all cells in order. Relative paths (e.g. `data/`) assume the working directory is this folder. Required packages are those imported in the first cell.
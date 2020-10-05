# PhosphorosAuxData

Auxiliary data repository for Phosphoros template fitting tool.

## Getting the last package from the GUI

When launching Phosphoros GUI, it will check if a newer data package is available here and ask your confirmation for performing an update if needed.

## Getting the last package from the CLI

Phosphoros provide a tool for handling the data package. To get the details of its usage run: 
```
> Phosphoros update_data_package --help
```

## Content of this repository:

The data packages are expected to be named following

AuxiliaryData_<version>.tar.xz

where <version> = major.minor (as exemple 0.1, 1.0, 2.4, ...)

they should contains the AuxiliariData folder with the Filters, ReddeningCurves and SEDs sub-foldres filled with actual data

The packages must be placed into the Data directory and the last_version.html must contains the <version> 


├── Data
│   ├── AuxiliaryData_0.1.tar.xz
│   └── AuxiliaryData_0.2.tar.xz
└── last_version.html

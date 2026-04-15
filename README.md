# weather_scrapping
getting info about cities, their corresponding weather, and summarising data

# Getting Started!
1. fixed encoding issues, as arrows are not supported by `CP1252` unlike `UTF-8` which can support any, we can do this terminal level or reading operation level by specificing `UTF-8`, in system level we use `sys.stdout` to modifiy terminal behavior, for `read(encoding='utf-8')`
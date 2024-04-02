Simple ruby script to filter failed and broken test file names for reruns from Allure csv report

### Installation:
1. Clone the repository
2. Give script executable permission with command `chmod +x allure_csv_filter`

### Usage:

The script awaits only one argument - filepath to allure csv report file

```sh
./allure_csv_filter <path to csv file>

./allure_csv_filter ~/Downloads/allure_suites.csv
```

### Output format
```sh
all scenarios count: 361
failed scenarios count: 12
failed unique files count: 9

path/to/file1
path/to/file2
...
path/to/file3
```

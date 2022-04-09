# User Api Testing using jmeter.
1. Download the .jmx file
2. Open Git bash CMD or your CLI mode in the download folder
3. Type the following commands:
```
jmeter -n -t [name of the .jmx file] -l [name of the reports.csv file] -e -o [blank folder name to generate html report]
```
4. here ```-n``` instruct jmeter run the test in non-GUI mode ```-t``` specify the path of .jmx file. ```-l``` instruct to write into log file results ```-e``` ```-o``` location of the output folder

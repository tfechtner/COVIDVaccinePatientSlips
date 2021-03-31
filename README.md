
# COVID Vaccine QR Generator
A free tool that allows you to convert a CSV list of patients into a printable pack of patient slips to make using Pinnacle a breeze.

## Why Use It?
Looking up patients in Outcomes4Health takes so long many vaccine sites are pre-registering patients (which takes hours). Part of the issue is transcribing NHS number and DOB (in the very specific format it demands).

This takes your list of patients for a vaccine session and for each patient generates a slip with a QR code for their DOB and NHS Number so they can be entered into Outcomes4Health rapidly using barcode scanners that vaccine sites have available. 

| Sample Sticker QR |
| ------------- |
| ![](img/demo_sticker_v2.png?raw=true)  |

##  Testing
There is a [dummy patient csv](docs/dummy-patient-list.csv?raw=true) file you can download here to try it.

## Run On Your Computer

 - [Download](COVIDVaccinePatientSlips_v1.5.0.zip?raw=true) the file package
 - Extract the zip file (right click on the file->Extract All). This step is very important as it will not run if opened from double clicking on the zip file.
 - Open "index.html" in Chrome, Firefox or Safari 
 - Follow the on-screen instructions
 - Print out the patient slips
 - Use barcode scanners to scan DOB and NHS number into Outcomes4Health

## IG and Security
No data is transferred anywhere when using this tool, all the process is done in your web browser. The tool uses some open source libraries to work. Using the tool is entirely at your own risk.

# VIN Decoder
This handy, Python-based code that I have developed can be used to decode Vehicle Identification Numbers (VIN) for as many vehicles as the user wishes want. The National Highway Traffic Safety Administration (NHTSA) public VIN Decoding API is employed to pull the relevant information. Based on my experience working on multiple projects, the following attributes are found the most relevant and will be pulled as part of this code:
- VIN
- Make
- Model
- ModelYear
- BodyClass
- ElectrificationLevel
- ErrorCode
- FuelTypePrimary
- FuelTypeSecondary
- VehicleType

However, the user can add/subtract any piece of vehicle attribute (showing up as columns in the final file) by revising the code slightly.

## Instructions:
1. Create a CSV file of the VINS, name it `VIN.csv`, put all the VINs in the first column with no heading. The code works even when the VINs are placed in different columns and even with the column header, but the column header will be shown as an empty row in the final output
2. Copy the VIN.csv file to the same folder as the Notebook file and run the first and second code blocks of the file.
3. Determine the columns (vehicle attributes) of the final output based on your needs by revising the 3rd block of code and, specifically, the `required_columns` variable.
4. Run the 3rd block of code and locate your final output file, named `VIN_pulled_data.csv` in the same folder as your Notebook.
--------------
<b>Please use this code and the free NHTSA VIN Decoding API responsibly by not overloading or misusing this free feature.  We do not want NHTSA to turn this awesome feature into a paid/subscription-based feature. Thanks you!</b>

-------------
Let me know if you have any questions and comments at mahdipn[at]gmail[dot]com

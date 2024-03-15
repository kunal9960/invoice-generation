# Invoice Generator 📑

This Python script automates the creation of PDF invoices from Excel files. 
Each row in the Excel file represents an invoice, and the script generates corresponding PDF invoices.


![Excel2pdf](https://github.com/kunal9960/invoice-generation/blob/master/Excel%20to%20pdf.png)


## Requirements

- Python 3.x
- Pandas
- FPDF

## Usage

This project uses the [Pandas](https://pandas.pydata.org/) library for Excel handling and [FPDF](https://fpdf.org/en/doc/index.php) library for PDF generation.

1) Install required packages:
- Pandas
   ```
   pip install pandas
   ```
- FPDF
   ```
   pip install fpdf
   ```
   
2)  Place all your excel files in the folder `invoices` in the same directory as main.py.
   
3)  Run the script:
```
python main.py
```

4)  Sit back and watch as the invoices are generated in PDF format.


## Example Screenshot

![Example](https://github.com/kunal9960/invoice-generation/blob/master/Example.png)


## Customization
You can customize various aspects of the generated PDF invoices.

- **Invoice Template:** Modify the template to match your branding and layout preferences.
- **Data Mapping:** Adjust how data from the Excel file is mapped to the PDF invoice fields in the script.
- **Styling:** Customize fonts, colors, and other styling elements to align with your brand identity.


## Contributing
Contributions are welcome! If you have any ideas for improvements or new features, feel free to fork the repository and submit a pull request. You can also open an issue to report bugs or suggest enhancements.

## Acknowledgments
Feel free to contact me if you need help with any of the projects :)

# Sanitized international demo package

This package is prepared for product documentation and demonstrations. Identifiers, cell names, SN values and coordinates are synthetic or translated. It does not contain customer network data.

## Demo workflow

1. Import `inputs/Network_Cell_Info_demo.xlsx`.
2. Import `inputs/PRB_Load_Data_demo.xlsx`.
3. Run the international EXE with the same analysis configuration used for the verified sample.
4. Review the Step 2 candidates, Step 3 decisions and Step 4 HTML report in `outputs/`.

## Included materials

- `inputs/`: English engineering and performance workbooks with anonymized identifiers.
- `outputs/2_Load_Balancing/candidates_sample.csv`: a concise sanitized Step 2 candidate sample.
- `outputs/3_Expansion_Reduction/step3_decisions_en_sample.csv`: a concise sanitized Step 3 decision sample.
- `outputs/4_Final_Reports/Network_Report_demo.html`: sanitized Step 4 HTML report.
- `screenshots/demo_preview.png`: visual preview of the sanitized inputs.
- `screenshots/step2_results_preview.png`: dedicated Step 2 candidate preview.
- `screenshots/step3_results_preview.png`: dedicated Step 3 decision preview.
- `screenshots/step4_report_preview.png`: Step 4 HTML report preview.

The result files preserve the original source-to-candidate direction and relative engineering relationships for demonstration. They are sanitized presentation artifacts; a new run with different parameters or software versions can produce different counts.

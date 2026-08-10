# Sanitized international demo package

This package is prepared for product documentation and demonstrations. Identifiers, cell names, SN values and coordinates are synthetic or translated. It does not contain customer network data.

## Demo workflow

1. Import `inputs/Network_Cell_Info_demo.xlsx`.
2. Import `inputs/PRB_Load_Data_demo.xlsx`.
3. Run the international EXE with the same analysis configuration used for the verified sample.
4. Review the Step 2 candidates, Step 3 decisions and Step 4 HTML report in `outputs/`.

## Included materials

- `inputs/`: English engineering and performance workbooks with anonymized identifiers.
- `outputs/2_Load_Balancing/candidates.csv`: sanitized Step 2 candidate results.
- `outputs/3_Expansion_Reduction/step3_decisions_en.csv`: sanitized Step 3 decision results.
- `outputs/4_Final_Reports/Network_Report_demo.html`: sanitized Step 4 HTML report.
- `screenshots/demo_preview.png`: visual preview of the sanitized inputs and results.
- `outputs/4_Final_Reports/run_manifest_demo.json`: non-sensitive demo manifest and file hashes.

The result files preserve the original source-to-candidate direction and relative engineering relationships for demonstration. They are sanitized presentation artifacts; a new run with different parameters or software versions can produce different counts.

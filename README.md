# VBA-Current-FY-Tracking-Automation
VBA tool automating the collection and formatting of SAP financial data for the current fiscal year Activated via a "Run Automation" button, it connects to SAP and pastes data into the "data" sheet based on specific reports and formats:

FS10N (Cash Out GL): Data to L2, light yellow background, category formula in column R.
S_ALR_87012103 (Cash Out Vendor): Data to first empty cell in column L, category formula in R.
FS10N (Cash In GL): Data to D2, light yellow background, category formula in J.
S_ALR_87012197 (Cash In Customer): Data to first empty cell in column D, category formula in J.

Additional formatting:
Columns D and L are highlighted orange if D, H, L, or P contain "C300".
Table structure in "data" tab must remain unchanged; formulas should exist in cells J2 and R2.

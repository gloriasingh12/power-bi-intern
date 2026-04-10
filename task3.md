### REAL-TIME STREAMING DASHBOARD

**Objective:** Create a Power BI Dashboard that updates automatically using a Streaming Dataset.

**Key Components:**
1. **Data Source:** Simulated API feed using Power BI "Streaming Dataset" (API method).
2. **Setup:** - Created a 'Push' Dataset in Power BI Service.
   - Defined real-time fields: Timestamp, TransactionID, and CurrentValue.
3. **Integration:** Used a Python script / PowerShell loop to push live JSON data to the API Endpoint.
4. **Visuals:** Added a 'Real-time Line Chart' and 'Gauge' that refresh in sub-second intervals.

**Deliverable:** A live dashboard showing continuous data flow without manual refresh.

# REST API Data Pipeline

## Steps Implemented

1. **Fetch Data**  
   - Retrieved data from the REST API URL.

2. **Convert to JSON**  
   - Converted the API response into a JSON file for processing.

3. **Custom Schema Creation**  
   - Designed a custom schema to properly map the JSON structure.

4. **Flatten JSON**  
   - Flattened the nested JSON fields using `.*` since the data was in `struct` type.

5. **Save as Delta Table**  
   - Stored the processed data as a **Delta Table** in Unity Catalog (UC).

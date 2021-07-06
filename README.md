# nyc-crashes

## Contributors: Hoang Minh Nguyen
 
 ## Description
    
  
   ### Usage: file: 'data_100000.csv' de Newyork City. Prepare data for model ML.
   ### Cleaning data base:
       1. drop columns :['contributing_factor_vehicle_3',
                'contributing_factor_vehicle_4',
                'contributing_factor_vehicle_5',
                'vehicle_type_code_3',
                'vehicle_type_code_4',
                'cross_street_name',
                'vehicle_type_code_5',
                'location'],
                
       2. read total_nan_values=51104
       3. df.dropna(how='all')
       4. drop duplicated 
       5. replace '' by np.nan
       6. convert date / time
       7. "strip" and "lower_case" in the columns:
       9. clean "text" of columns (not yet finish)
      10. file output after cleaning:  'data_clean_GOOD_ENOUGH.csv' ,'data_clean_GOOD.csv'

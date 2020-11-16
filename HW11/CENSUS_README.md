# if you are having a hard time finding the census data you can use these files that I had saved in the repo in the data folder:

# [dec_00_sf1_dp1.csv](../data/dec_00_sf1_dp1.csv)

# [dec_10_sf1_sf1dp1.csv](../data/dec_10_sf1_sf1dp1.csv)

# Column names to use.
cols00 = {'geo_id2': 'id', 'geo_display_label': 'label',
          'hc01_vc01': 'Population', 'hc01_vc18': 'MedianAge',
          'hc02_vc48': 'PercWhite'}

cols10 = {'geo_id2': 'id', 'geo_display_label': 'label',
          'hd01_s001': 'Population', 'hd01_s020': 'MedianAge',
          'hd02_s100': 'PercWhite'}

# Select subset of downloaded data to use.
c00 = census00[['geo_id2', 'geo_display_label', 'hc01_vc01',
                'hc01_vc18', 'hc02_vc48']].copy().rename(columns=cols00)
c10 = census10[['geo_id2', 'geo_display_label', 'hd01_s001',
                'hd01_s020', 'hd02_s100']].copy().rename(columns=cols10)
                
                
                
Finding the census data on your own is extra credit then

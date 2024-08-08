SONUÇLAR
 SaleId   SaleDate CheckInDate  Price     ConceptName SaleCityName  \
0  415122 2022-12-03  2022-12-03  79.30    Herşey Dahil      Antalya   
1  415103 2022-12-03  2022-12-03  45.97  Yarım Pansiyon      Antalya   
2  404034 2022-09-12  2022-09-13  77.84    Herşey Dahil      Antalya   
3  415094 2022-12-03  2022-12-10 222.71  Yarım Pansiyon        İzmir   
4  414951 2022-12-01  2022-12-03 140.48  Yarım Pansiyon        İzmir   

     CInDay  SaleCheckInDayDiff Seasons  
0  Saturday                   0     Low  
1  Saturday                   0     Low  
2   Tuesday                   1    High  
3  Saturday                   7     Low  
4  Saturday                   2     Low  
(59164, 9)
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 59164 entries, 0 to 59163
Data columns (total 9 columns):
 #   Column              Non-Null Count  Dtype         
---  ------              --------------  -----         
 0   SaleId              59164 non-null  int64         
 1   SaleDate            59164 non-null  datetime64[ns]
 2   CheckInDate         59164 non-null  datetime64[ns]
 3   Price               59151 non-null  float64       
 4   ConceptName         59164 non-null  object        
 5   SaleCityName        59164 non-null  object        
 6   CInDay              59164 non-null  object        
 7   SaleCheckInDayDiff  59164 non-null  int64         
 8   Seasons             59164 non-null  object        
dtypes: datetime64[ns](2), float64(1), int64(2), object(4)
memory usage: 4.1+ MB
None
6
SaleCityName
Antalya    31649
Muğla      10662
Aydın      10646
Diğer       3245
İzmir       2507
Girne        455
Name: count, dtype: int64

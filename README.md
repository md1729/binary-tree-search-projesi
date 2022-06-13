# binary-tree-search-projesi
# binary tree search gösterimi
root5
7 ekledik  sağ tarafa(7>5) 
	   5	
		\
		      7

1 ekledik sol tarafa(1<5)
			5		
		/		\	
	1				7
					
					

 sağ tarafa 8 ekledik (5<8 & 7<8)
			5				
		 /		  \			
	 1				7		
						\	
							8
							
							

5 in sağına 7 nin soluna 6 ekledik
			5				
		/		\			
	1				7		
				/		\	
			6				8
							

3 ekledik 5 soluna ve 1 in sağına
								5						
						/			\					
					1					7				
						\			/		\			
							3	6				8		
														
														
														



0 ekliyoruz 5 ten küçük olduğu için soluna ve 1 den küçük olduğu içinde sol tarafına 1 in 0 koyarız.
					5				
			/			\			
		1					7		
	/		\			/		\	
0				3	6				8

9 u 5 in sağına ,7 nin sağına ve 8 in sağına gelecek şekilde ekliyoruz
						5									
					/			\							
				1					7						
			/		\			/		\					
		0				3	6				8				
												\			
													9		

4 sayısı 5 in soluna,1 sağına,3 ün sağına gelecek şekilde ekliyoruz
						5									
					/			\							
				1					7						
			/		\			/		\					
		0				3	6				8				
							\					\			
								4					9		

2 sayısını 5 in soluna 1 in sağına ve 3 ün soluna gelecek şekilde ekliyoruz.
						5									
					/			\							
				1					7						
			/		\			/		\					
		0				3	6				8				
					/		\					\			
				2				4					9		


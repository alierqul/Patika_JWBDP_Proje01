# Java ile Backend Web Development Patikası

## Veri Yapıları ve Algoritmalar  


## Proje Ödevi  -02

### [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

## Çözüm
Merge Sort; Adı üstünde parçala ve sırala. 
Bir listeyi tek elemanlı hale gelene kadar parçalışıyoruz. 
Parçaladıktan sonra sıralayarak tekrar birleştiiyoruz.


							[16,21,11,8,12,22]
							[16,21,11] 		[8,12,22]
					  [16,21]	 [11] 			[8,12] 	[22]
			    [16] 	[21]	 [11]	 [8] 	[12]	 [22]
				  [16,21] 			[8,11]			[12,22]
						  [8,11,16,21]		[12,22]	
							  [8,11,12,16,21,22]
							  
$$
	2^{x} =n 
$$

log n kez tekrarlanıyor. Big-O = O(nLogn)


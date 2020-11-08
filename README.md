# Error_zip

> **Icnnv**
* file_example <- data.table(read_csv("C:/file_example.csv", locale = locale(encoding = "UTF-8")))
* 애초에 UTF-8로 읽어 오거나, 되어 있다면 ->
* query = URLencode(iconv(file_examplig[1]$character,from = "UTF-8", to="UTF-8")) 이렇게 써야함 
* if, 단순히 query = URLencode(iconv(file_examplig[1]$character, to="UTF-8")) 이렇게만 쓴다면 결과값은 모두 NA로 찍힘 






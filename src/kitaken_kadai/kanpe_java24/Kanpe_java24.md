#Q. kanpe10
ArrayListのメリットとデメリットをHashMapのメリットとデメリットとして比べて言える
#A.
* **ArrayListのメリット**
	* 複数の同じ分類分けされた要素がある場合に使える。
		* 例)一つのテスト(という分類)の平均点を求めたい場合など。
	* keyが数字の昇順でも構わない場合に使える。
		* 出席番号1番からテストの点数を格納していきたい場合など。
	* keyの衝突が発生しない。
	* keyを指定する必要がないため要素の追加が容易。
* **ArrayListのデメリット**
	* valueがどのようなvalueなのか、添字からはわからない。

* **HashMapのメリット**
	* 添字が数字では分かりづらい場合に用いる。
		* 例)生徒の名前毎にテストの点数を格納していきたい場合など
	* valueがどのようなvalueなのかkeyを見れば直感的に分かる。
* **HashMapのデメリット**
	* keyの衝突が発生しないように管理しなければならない。
	* 要素を追加する場合はvalueと一緒にkeyも追加しなければならない。
	
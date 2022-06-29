# str-to-raw
## 很实用的函数，可将字符串形式的列表、字典、元组等还原
def raw(s):

	a = {}

	exec("a = " + s,a)

	return a["a"]

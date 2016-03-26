## brat
brat官网的版本不支持中文输入，只需在./server/src/projectconfig.py注释掉第162行，并在第163行加入n  = re.sub(u'[^a-zA-Z\u4e00-\u9fa5<>,0-9_-]', '_', n)即可。这个版本是改后的。

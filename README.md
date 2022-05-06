# css 总结
```
.loop( @count )when( @count > 0 ){ 
	.m@{count}{ margin: ( 1px * @count ); } 
	.mt@{count}{ margin-top: ( 1px * @count ); } 
	.mb@{count}{ margin-bottom: ( 1px * @count ); } 
	.ml@{count}{ margin-left: ( 1px * @count ); } 
	.mr@{count}{ margin-right: ( 1px * @count ); } 
	.p@{count} {padding: (1px * @count); } 
	.pt@{count}{ padding-top: ( 1px * @count ); } 
	.pb@{count}{ padding-bottom: ( 1px * @count ); } 
	.pl@{count}{ padding-left: ( 1px * @count ); } 
	.pr@{count}{ padding-right: ( 1px * @count ); } 
	.f@{count}{ font-size: ( 1px * @count ); } 
	.w@{count}{ width: ( 1px * @count ); } 
	.h@{count}{ height: ( 1px * @count ); } 
	.loop((@count - 1)); 
} 
.loop(100);
```
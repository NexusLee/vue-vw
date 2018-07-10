## vue viewport 方案
```
.test { 
  border: .5px solid black; 
  border-bottom-width: 4px; 
  font-size: 14px; 
  line-height: 20px; 
  position: relative;
} 
[w-188-246] { 
  width: 188px; 
}
```
#### 编译出来的CSS：
```
.test { 
  border: .5px solid #000; 
  border-bottom-width: .533vw; 
  font-size: 1.867vw; 
  line-height: 2.667vw; 
  position: relative; 
} 
[w-188-246] { 
  width: 25.067vw; 
}
```

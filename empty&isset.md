### empty() 判斷輸入值是否為空 ( null )
### isset 判斷「變數有沒有被賦值」
```
 // $a 不設置
  $b = null;
  $c = 0;
  $d = 1;
  $e = "";
  $f = "abc";

  // 變數是否設置 ?
  echo isset($a); // $a 不存在 => FALSE 
  echo isset($b); // $b = null => FALSE
  echo isset($c); // $c = 0 => TRUE 
  echo isset($d); // $d = 1 => TRUE
  echo isset($e); // $e = "" => TRUE
  echo isset($f); // $f = "abc" => TRUE

  // 變數內值是否為空 ? 沒有就回傳 1 ( TRUE )
  echo empty($a); // $a 不存在 => TRUE
  echo empty($b); // $b = null => TRUE
  echo empty($c); // $c = 0 => TRUE 
  echo empty($d); // $d = 1 => FALSE
  echo empty($e); // $e = "" => TRUE
  echo empty($f); // $f = "abc" => FALSE
  ```

# pics
其他地方引用的照片

引用方式
```
![git](https://github.com/qlong8807/pics/raw/master/leanote/名称.jpg)
```

<details>
  <summary>折叠文本</summary>
  此处可书写文本
  这里是被折叠的文本。
  <pre><code> 
CREATE OR REPLACE PROCEDURE stu_proc(v_name IN VARCHAR2, v_id OUT NUMBER) AS
--声明语句段
BEGIN
    --执行语句段
    SELECT seq_matching_record_detail.nextval INTO v_id FROM DUAL;
    EXCEPTION
    --异常处理语句段
    WHEN NO_DATA_FOUND THEN 
        dbms_output.put_line('NO_DATA_FOUND');
END;



DECLARE
  i NUMBER ;
BEGIN
      stu_proc('张三',i);
      dbms_output.put_line('查询到的ID为： '||i);
END;
</code></pre>
</details>

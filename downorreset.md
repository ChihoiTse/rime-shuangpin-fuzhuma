2024-5-9

- flypy_flypy.schema.yaml	

  ```
  enable_user_dict: true
  
  
  punctuator:
    full_shape:
      __include: default:/punctuator/full_shape  # 从 default.yaml 导入配置
    half_shape:
      __include: default:/punctuator/half_shape  # 从 default.yaml 导入配置
    symbols:
      __include: symbols_big_v:/symbols         # 从 symbols_caps_v.yaml 导入配置
  ```

- custom_phrase_own.txt

  - ```
    
    ```

- symbols_onw_v.yaml

  - `C:\software\Rime\weasel-0.15.0\data\cn_dicts_xh\user.dict.yaml`

- 标点符号自动上屏的配置是在default.yaml的punctuator:half_shape


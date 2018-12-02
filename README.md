## phalcon 的验证工具

#### 
``` php
use Phalcon\Validation;
use PhalconValidators\IDCard;

$validation = new Validation();

$validation->add(
    "idcard",
    new IDCard(
        [
            "message" => "身份证号错误",
        ]
    )
);
```
# Sequence Diagram
![uml](http://www.plantuml.com/plantuml/png/ZP713e8m44Jl_Gf-m1_mO30atZo8YNSYSsXSMjrk9VozBGrOKHAFCs-dcywMJXeMtv6gICD8iTaL1suwz9PlswB6myE9cgsHQnBmFgF9-2TRMnz6tp3fI2fhX2tHnykP6MUEjWK5VFBWGIKL_JFugQ-OoQJpJ0tdIRBGOk585_ik6ds0qGtTg55-_TBThN5OhMZ2Antz2ATBPDaIfWqdUW40)

# Data Format
## Request
```php
class Request {
    public $server;
    public $get;
    public $post;
    public $files;
    public $cookie;
    public function lock();
}
```
## Content
```php
= array
```
## Response
```php
class Response {
    public $statusCode;
    public $contentType;
    public $stream;
}
```

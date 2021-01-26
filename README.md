<h2> Hi, I'm Sensei George! <img src="https://media1.giphy.com/media/3N5r5Ks7vo3f2/giphy.gif" width="50"></h2>
<img align='right' src="https://media4.giphy.com/media/PiQejEf31116URju4V/giphy.gif?cid=ecf05e47l7tqpnkal0ajb1gxtptrm0b8ragkcwh4de3w6qa2&rid=giphy.gif" width="230">
<p><em>Software Enginner at <a href="http://www.unb.br">Fontys University</a><img src="https://media.giphy.com/media/fYSnHlufseco8Fh93Z/giphy.gif" width="30"></br>Developer / Student 
</em></p>


### <img src="https://media1.giphy.com/media/PMExYMdOHKfa6GU32L/giphy.gif" width="50"> A little more about me...  

```php
<?php

namespace Gogbog;

class About extends Me
{
    public function getWorkspace(): array
    {
        return [
            'workplace' => [
                'company' => 'Veniway',
                'position' => 'Backend Developer'         
            ]
        ];
    }

    public function knowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Java::class,
            Mysql::class,
            Docker::class,
            Centos::class,
            Linux::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Be at the top of the game';
    }
}
```


---

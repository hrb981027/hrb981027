```php
<?php

namespace github;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'Alibaba',
                'position' => 'PHP & JAVA Developer'
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Php::class,
            Go::class,
            Java::class,
            Linux::class
        ];
    }

    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}
```

<img src="https://cdn.jsdelivr.net/gh/sy-records/staticfile@master/images/202007/huaji.gif" align="right" height="195">

![Hemant Joshi Github Stats](https://github-readme-stats.vercel.app/api?username=hrb981027&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)

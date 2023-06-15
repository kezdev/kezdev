# Hey, I'm Kez 👋🏻

```php
<?php

namespace KezHall;

class About extends Me
{
    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            ReactNative::class, // debatable
            TailwindCss::class,
        ];
    }
    
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Nimbus Hosting',
                'position' => 'Developer'         
            ]
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To finally complete a side project.';
    }
}

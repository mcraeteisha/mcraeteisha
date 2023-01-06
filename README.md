```php
<?php

namespace TeishaMcRae;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'ProcessMaker',
                'position' => 'Jr. Software Engineer'         
            ]
        ];
    }
    
    public function getMoreInfo(): array
    {
        return [
            'fun_facts' => [
                'pronouns' => 'she, her',
                'book_lover' => true,
                'cat_mom' => true         
            ]
        ];
    }

    public function getCodingKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            React::class,
        ];
    }
}
```

<!---
mcraeteisha/mcraeteisha is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

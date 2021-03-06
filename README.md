<h1 align=center> Hello World! š </br> Harits Rahman Mazayamusthafa</h1>
<p align=center>
  <img src="https://img.shields.io/discord/980034204236668958?style=flat" />
  <img src="https://img.shields.io/github/followers/rietzche?style=flat" />
  <a href="https://github.com/sponsors/rietzche"><img src="https://img.shields.io/static/v1?label=Sponsor%20rietzche&message=%E2%9D%A4&logo=GitHub" /></a>
  <img src="https://visitor-badge.laobi.icu/badge?page_id=rietzche.rietzche" />
</p>
<!--
**rietzche/rietzche** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->

<!-- ![](https://github.com/rietzche/rietzche/blob/main/header.png) -->

```php
/**
*
* My Name is Harits Rahman Mazayamusthafa
*
*/

<?php

namespace Facades\Rietzche;

use Facades\Rietzche\Media;
use Facades\Rietzche\Profile;
use Facades\Rietzche\Development;

class Intro
{

  /**
  * __invoke()
  * 
  * @params array $learning
  * @return error
  */
  public function __invoke(array $learning)
  {
    Profile::name = 'Harits Rahman Mazayamusthafa';
    Profile::alias = 'Rietzche';
    Profile::email = 'haritzrahman98@gmail.com'; // Email address is already taken
    
    Media::instagram = Media::twitter = '@haritsrm';
    
    Development::langs = [
      'backend' => 'php:laravel|javascript:node-js|java|python',
      'frontend' => 'javascript:react-js,vue-js',
      'database' => 'postgresql|mysql|mongodb|sqlite|elasticsearch|redis'
    ];
    Development::misc = [
      'devops' => 'gcp:gke,gcloudrun,gce|aws:ecs,ec2,s3|heroku',
      'tools' => 'terraform|cloud cli',
      'os' => 'mac-os'
    ];
    Development::experience = carbon('2017')->diffInYears();
    
    return $this($learning);
  }
  
}

```

```
- š„± I am currently working on backend:java,php|devops:gcp,aws.
- š Available for Freelance projects opportunities.
```
<p align=center>
<a href="https://github.com/rietzche"><img align="center" src="https://github-readme-stats.vercel.app/api?username=rietzche&show_icons=true&theme=nord&hide_border=true&hide_title=true&count_private=true&include_all_commits=true" alt="rietzche github stats" /></a><a href="https://github.com/rietzche"><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rietzche&layout=compact&theme=nord&hide_border=true&hide=CSS,HTML,Blade&count_private=true" /></a>
</p>

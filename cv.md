# My Curriculum vitæ (i.e. Resume :scroll:)

1. **First Name, Last Name**

    Alexander, Luboshenko

1. **Contact Info** _(add several ways to contact you)_

    - Skype: alexander.luboshenko
    - DISCORD: Petrovich#9327

1. **Summary**
_(your goal, wishes, reveal what is important for you, what do you want and why._
_Some kind of self-presentation. In case of lack of experience Junior Developer sells his/her potential, his/her passion and ability to learn fast. You shouldn't think that everybody is going to teach you when you come to the workplace. Rather being a Junior means always learning new things from everywhere etc.)._

1. **Skills** _(e.g. programming languages, frameworks, methodologies, version control, tools etc.)_
    * Programming languages
        * C#.NET (2003 - 2009, 2014 - Now)
        * Java (2009 - 2014)
        * Javascript (2003 - now)
        * Transact SQL
        * PL/SQL
        * Node.js
    * Frameworks
        * .NET Framework
        * Spring
    * Methodologies
        * Kanban
        * Scrum
    * Version Controls
        * git
        * svn
        * TFS

1. **Code examples** _(LATEST)_
```
    const getAuthToken = (expired) => {
    const emailServiceTokenCacheKey = 'EmailServiceToken';
    let token;
    if(!expired) {
        token = cache.get(emailServiceTokenCacheKey);
    } else {
        cache.expire(emailServiceTokenCacheKey);
    }
    if(!token) {
        token = api.post(uAPIConfig.idService.getTokenUrl, {
        client_id: emailServiceConfig.apiKey,
        client_secret: emailServiceConfig.apiSecret,
        scope: emailServiceConfig.scope
        });
        cache.set(emailServiceTokenCacheKey, token, token.expires_in);
    }
    return token;
    };
```

1. **Experience**
_(for a Junior Dev it means all kinds of experience: coding tests, projects from courses, freelance projects - wherever they had the opportunity to demonstrate skills they have. Also it would be awesome if you add links to source code)_
    * 1997 - 2003: Development of web sites as a freelance worker (An example: [6x9.ru](http://6x9.ru));
    * 2003 - 2007: Software engineer at [NVP Modem](https://www.modem.by/en/), C#.NET
    * 2007 - 2009: Software engineer at [Actimind](http://www.actimind.com/), C#.NET
    * 2009 - 2014: Software engineer at [Intervale](http://intervale.ru/), Javascript, Java
    * 2014 - ....: Software engineer at [EPAM Systems](http://www.epam.com/), C#.NET, Node.js, Javascript

1. **Education** _(including courses, seminars, lectures, online learning)_
    * 1994 - 1999: Francisk Skorina Gomel State University, Mathematics faculty
    * 1991 - 1994: Gomel State Road Construction College, Maintenance and Repairing of Electronic and Computing Equipment faculty

1. **English** _(elaborate on what kind of practice you had, if any, how long it lasted and so on)_

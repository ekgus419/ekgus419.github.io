---
layout: default
---

# $ cat about-me.txt
{:id="about"}
문제 해결, 문서화, 명확한 의사소통을 중시하며 <br />
지속적인 학습과 성장을 통해 전문적이고 신뢰할 수 있는 개발자가 되기 위해 노력하고 있습니다.<br />
{% for me in site.categories.about %}<a href="{{ me.url }}" title="{{ me.description }}">more info</a>{% endfor %}

# $ cat work-experience.txt
{:id="works"}
5년차 웹 개발자입니다.<br />
쇼핑몰 플랫폼에서 다양한 프로젝트 경험을 갖고 있습니다.<br />
사용자 요구사항을 분석하고 구현하는데 능숙하며 주로 유지보수 업무를 담당해왔습니다.<br />
{% for work in site.categories.works %}<a href="{{ work.url }}" title="{{ work.description }}">more info</a>{% endfor %}

# $ cat education-certificate.txt
{:id="edu"}
지속적인 발전을 위해 학위 취득, 자격증 취득 등 끊임없이 노력해왔습니다.<br />
{% for edu in site.categories.edu %}<a href="{{ edu.url }}" title="{{ edu.description }}">more info</a>{% endfor %}

# $ cat skills.txt
{:id="skills"}
업무 및 토이 프로젝트를 통해 사용 및 습득 하였던 기술들을 정리하였습니다.<br />
{% for skill in site.categories.skills %}<a href="{{ skill.url }}" title="{{ skill.description }}">more info</a>{% endfor %}

# $ cat toy-project.txt
{:id="toy"}
평소 관심 있었던 분야 및 아쉬움이 남았던 프로젝트들을 구현해보았습니다.<br />
{% for list in site.categories.toy %}<a href="{{ list.url }}" title="{{ list.description }}">more info</a>{% endfor %}

# $ cat improvements-experience.txt
{:id="improvements-experience"}
개선 및 문제 해결 사례중 인상 깊었던 프로젝트 사례들을 정리하였습니다.<br />
{% for example in site.categories.improvements-experience %}<a href="{{ example.url }}" title="{{ example.description }}">more info</a>{% endfor %}

# $ cat contact.txt
{:id="contact"}
[resume](https://ekgus419.github.io/myportfolio/portfolio.pdf)<br />
<ul>
<li><a href="https://dh-0419.tistory.com" target="_blank" title="Blog">Blog</a></li>
<li><a href="https://github.com/ekgus419" target="_blank" title="GitHub">GitHub</a></li>
<li><a href="mailto:ekgus419@gmail.com" target="_blank" title="제게 연락해주세요!">Send mail</a></li>
</ul>
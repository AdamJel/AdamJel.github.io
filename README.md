# Adam Jelinek's e-CV

hello from github pages

{% include_relative docs/test_1.md %}

{% capture my_include %}{% include test_2.md %}{% endcapture %}
{{ my_include | markdownify }}

# VSCode Hexo Tag Syntax

Show code highlights inside hexo codeblock

## Usage

```
{% codeblock lang:typescript mark:3 %}
function ProfileTimeline() {
  // Try to read posts, although they might not have loaded yet
  const posts = resource.posts.read();
  return (
    <ul>
      {posts.map(post => (
        <li key={post.id}>{post.text}</li>
      ))}
    </ul>
  );
}
{% endcodeblock %}
```

```
{% codeblock mark:3 %}
function ProfileTimeline() {
  // Try to read posts, although they might not have loaded yet
  const posts = resource.posts.read();
  return (
    <ul>
      {posts.map(post => (
        <li key={post.id}>{post.text}</li>
      ))}
    </ul>
  );
}
{% endcodeblock %}
```

![screenshot](docs/screenshot.png)

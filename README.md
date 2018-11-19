### Kitabu
---
https://github.com/fnando/kitabu

```
gem install kitabu
kitabu check
kitabu new mybook

curl -H "Content-Type:application/json" -d'{"user_credentials":"YOUR_CREDENTIALS_HERE", "doc":{"name":"kitabu.pdf", "document_type":"pdf", "test":"false", "document_url":"https://dl.dropboxusercontent.com/u/123456789/output/kitabu.pdf.html"}}' http://docraptor.com/docs > kitabu.pdf
```

```
<%= toc %>

<% note do %>
  Make sure you try .erb files!
<% end %>

<div class="note info">
  <p>
    Make sure you try .erb files!
  </p>
</div>

<% note :warning do %>
  Make sure you write valid ERB code.
<% end %>
```

```ruby
class User < ActiveRecord::Base
  validates_presence_of :login, :password, :email
  validates_uniqueness_of :login, :email
end
```

```php
echo "Hello";
```

```scss
@font-face {
  font-family: 'Open Sans Condensed Bold';
  src: url('../fonts/OpenSans-CondBold.ttf');
}

```


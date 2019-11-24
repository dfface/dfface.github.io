---
title: "留言"
permalink: "/contact.html"
---

<form action="https://formspree.io/mbjjnedo" method="POST">    
<p class="mb-4">欢迎发送消息到 {{site.name}}，我会尽可能快地回复您！</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="昵称*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail 地址*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="消息内容*" required></textarea>    
<input class="btn btn-success" type="submit" value="发送">
</form>   
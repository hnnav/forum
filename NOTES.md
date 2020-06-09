Rails forum

Users
has_many :posts
has_many :comments
username
password_digest

Posts
belongs_to user
has_many :comments
title
content

Comment * join table joining users & posts
belongs_to :user
belongs_to :post
content

( Categories )
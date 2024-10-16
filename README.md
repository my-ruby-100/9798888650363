# Ruby on Rails Background Jobs with Sidekiq

```
SIDEDKIQ_REDIS_URL
REDIS_PROVIDER
```

```
config/sidekiq.yml
```


```
#  http://localhost:3000/sidekiq
require ​"sidekiq/web"​
mount Sidekiq::Web => ​"/sidekiq"
```


```
sidekiq: ​bundle exec sidekiq
```

```
include​ Sidekiq::Job
```


## Ref

* <https://www.oreilly.com/library/view/ruby-on-rails/9798888650554/>
* <https://github.com/sidekiq/sidekiq/wiki>
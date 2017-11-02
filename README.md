# hello-world
Just another repository

过滤器的具体逻辑。这里我们通过 ctx.setSendZuulResponse(false) 令 zuul 过滤该请求，不对其进行路由
然后通过 ctx.setResponseStatusCode(401) 设置了其返回的错误码
当然也可以进一步优化我们的返回，比如通过ctx.setResponseBody(body)对返回的 body 内容进行编辑等

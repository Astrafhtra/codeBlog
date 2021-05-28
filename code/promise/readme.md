/**
 * promise是ES6提供的异步编程的解决方案,本事是一个构造函数
 * pending(进行中),resolved(已完成),reject(已失败)
 */

- 基本用法
  ``````js
  let promise = new Promise((resolve,reject)=>{
    resolve();
  }).then(res=>{
    console.log(res)
  })
  ``````````
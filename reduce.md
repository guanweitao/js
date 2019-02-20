1、reduce实现map，filter
let arr = [1,2,3,4]

const fn = (arr) => {
  arr.reduce((newArr, next) => {
    next = next*2;
    newArr.push(next)
    return newArr
  }, [])
}
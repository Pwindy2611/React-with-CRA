# useState Hook(trạng thái dữ liệu)
import {useState} form 'react'

funtion Component()
{
    const [counter,setCounter]=useState(1) => counter = 1
    
    return(
        ...
    )
}

* Component sẽ được render lại sau khi setState     
* giá trị mặc định chỉ được nhận khi gọi setState lần dầu những lần sau sẽ lấy giá trị trước đó
* Nếu muốn tạo giá trị mặc định dưới dạng return giá trị của 1 function thì nên cài funtion trực tiếp vào useState và viết dưới dạng arrow function

# useEffect Hook
import {useEffect} from 'react'
. Callback luôn được gọi sau khi component mounted
* useEffect(callback)
. gọi callback mỗi khi component re-render
. gọi callback sau khi component thêm element vào DOM
* useEffect(callback, [] )
. chỉ gọi callback 1 lần sau khi component mounted
* useEffect(callback,[dependencies])
. callback sẽ được gọi lại khi dependecies thay đổi (lính canh)

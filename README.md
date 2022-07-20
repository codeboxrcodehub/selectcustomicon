# Custom dropdown arrow/icon for select/dropdown in html

The dropdown arrow/icon in select/dropdown html  comes from browser's standard style. This repository will to implement a custom icon/arrow for the dropdown/select.

## Usage

#html

```
<div class="custom-select-arrow-wrap">
  <div class="custom-select-arrow">
    <select name="" id="" class="">
      <option value="option-1">Option 1</option>
      <option value="option-2">Option 2</option>
      <option value="option-3">Option 3</option>
      <option value="option-4">Option 4</option>
      <option value="option-5">Option 5</option>
      <option value="option-6">Option 6</option>
      <option value="option-7">Option 7</option>
    </select>
  </div>
</div>
```

#css

```
/*remove default down arrow*/
select {
    -webkit-appearance: none;
    -moz-appearance: none;
}

/*basic style*/
select {
    width: 100%;
    padding: 1rem;
    border-radius: 0.5rem;
    z-index: 1;
    background-color: transparent;
    position: relative;
}

.custom-select-arrow-wrap {
    position: relative;
}

.custom-select-arrow:before {
    font-family: "Font Awesome 6 Free";
    content: "\f107";
    z-index: 0;
    line-height: 2;
    font-weight: 900;
    color: #fff;
    background-color: #153E5D;
    width: 2rem;
    height: 2rem;
    border-radius: 0.5rem;
    position: absolute;
    top: 0.45rem;
    right: 1rem;
    text-align: center;
}
```

## Contributing

Contributions to this repo will be appreciated.


## License

Writelog is licensed under the [MIT License](http://opensource.org/licenses/MIT).

Copyright 2022 [Codeboxr](https://codeboxr.com)

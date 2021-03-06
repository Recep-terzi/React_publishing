# React_publishing

### React kullanarak npmjs.com sitesine kendi kütüphanemizi oluşturabiliriz.

### Yapılması gerekenler:

* İlk olarak işlemimizi yapacağımız klasörü oluşturuyoruz daha sonra cmd ekranından oluşturduğumuz dizinin içine girdikten sonra  "npm install -g create-react-library" diyoruz.

* Daha sonrasında cmd ekranına tekrardan "create-react-library" yazıyoruz. Çıkan sorulardan Package Name için kendi kütüphanemize vermek istediğimiz ismi giriyoruz. Bunun daha önce kullanılıp kullanılmadığı kontrolünü yapabilmek için ise https://remarkablemark.org/npm-package-name-checker/ adresini kullanabiliriz.

  ![](https://i.hizliresim.com/chcvery.PNG)

* Package Name belirledikten sonra gerekli işlemlere onay veriyoruz. Bu işlemleri yapabilmek için npmjs.com sitesine kayıt olmanız gerekmektedir.

* Kurulumlar tamamlandıktan sonra dosyalarımızı kullandığınız editörde açarak gerekli işlemleri yapıyoruz.

* İşlemleri yaptıktan sonra terminal ekranına tekrardan gelip buraya npm login diyerek login işlemini gerçekleştiriyoruz. (Username,Password,Email)

  ![](https://i.hizliresim.com/ip6uhue.PNG)

* Login işlemi yaptıktan sonra npm publish diyerek kütüphanemizi publish etmiş oluyoruz. İyi çalışmalar :)



## https://www.npmjs.com/package/pysonui

![](https://i.hizliresim.com/baoqlgn.png)

# pysonui

> Made with create-react-library

[![NPM](https://img.shields.io/npm/v/pysonui.svg)](https://www.npmjs.com/package/pysonui) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save pysonui
```

## Usage

```jsx
import React, { Component } from 'react'

import MyComponent from 'pysonui'
import 'pysonui/dist/index.css'

class Example extends Component {
  render() {
    return <MyComponent />
  }
}
```

## License

MIT © [Recep-terzi](https://github.com/Recep-terzi)


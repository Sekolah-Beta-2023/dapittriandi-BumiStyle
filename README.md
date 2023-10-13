## Bumi-Style-App
Bumi Style Adalah sebuah aplikasi ecommarce berbasis web , nama ini terinsiparasi dari istilah anak bumi yang sedang trend.

#aplikasi ini memiliki 5 menu yaitu:
1.homepage
2.product
3.about
4.user/pengguna
5.logout

#aplikasi ini terdapat beberapa fitur
1.fitur CRUD pengguna:
  -create pengguna dengan register 
  -get Pengguna by username
  -edit pengguna *fitur ini masih bermasalah karena terkena error cors*
  -dan fitu delete pengguna
2.fitur CRUD Product:
  -create product
  -Get product berdasarkan id
  -edit product berdasarkan id
  -delete product

#alur pemakaian aplikasi:
1.Tekan Tombol Masuk 
2.Kemudian Register terlebih dahulu kemudian submit
3.Setelah itu login Dengan username,email,dan password
4.kemudian akan di arahkan dengan preview data pengguna,kemudian pergi ke homepage setelah itu tap shop now
5.kemudian akan di arahkan ke halaman product 
6.dan kita dapat mengedit product seperti mengubah datanya, dan menghapus product dengan menekan button detail.
7.kemudian kita pergi ke halaman about untuk melihat tentang developer
8.setelah itu pergi ke halaman setting profil disN kita dapat update dan menghapus data pengguna, *namun untuk update data pengguna belum bisa karena terkena error cors*
9.kemudian kita bisa menekan tombol log out untuk keluar atau dengan menghapus akun otomatis logout.

*NOTE: disini baru bisa sebagai admin, belum bisa sebagai user*

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out the [documentation](https://nuxtjs.org).

## Special Directories

You can create the following extra directories, some of which have special behaviors. Only `pages` is required; you can delete them if you don't want to use their functionality.

### `assets`

The assets directory contains your uncompiled assets such as Stylus or Sass files, images, or fonts.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/assets).

### `components`

The components directory contains your Vue.js components. Components make up the different parts of your page and can be reused and imported into your pages, layouts and even other components.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/components).

### `layouts`

Layouts are a great help when you want to change the look and feel of your Nuxt app, whether you want to include a sidebar or have distinct layouts for mobile and desktop.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/layouts).


### `pages`

This directory contains your application views and routes. Nuxt will read all the `*.vue` files inside this directory and setup Vue Router automatically.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/get-started/routing).

### `plugins`

The plugins directory contains JavaScript plugins that you want to run before instantiating the root Vue.js Application. This is the place to add Vue plugins and to inject functions or constants. Every time you need to use `Vue.use()`, you should create a file in `plugins/` and add its path to plugins in `nuxt.config.js`.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/plugins).

### `static`

This directory contains your static files. Each file inside this directory is mapped to `/`.

Example: `/static/robots.txt` is mapped as `/robots.txt`.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/static).

### `store`

This directory contains your Vuex store files. Creating a file in this directory automatically activates Vuex.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/store).

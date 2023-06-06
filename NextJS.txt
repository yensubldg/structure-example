├── README.md
├── docker-compose.yml
├── package-lock.json
├── package.json
├── packages
│   ├── admin
│   │   ├── desktop.ini
│   │   ├── jsconfig.json
│   │   ├── package-lock.json
│   │   ├── package.json
│   │   ├── patches
│   │   │   └── tinymce+6.4.0.patch
│   │   ├── public
│   │   │   ├── images
│   │   │   │   ├── classic_layout.png
│   │   │   │   └── modern_layout.png
│   │   │   ├── index.html
│   │   │   ├── logo192.png
│   │   │   ├── logo512.png
│   │   │   ├── manifest.json
│   │   │   ├── resource
│   │   │   │   ├── tinymce.css
│   │   │   │   └── vi.js
│   │   │   └── robots.txt
│   │   ├── src
│   │   │   ├── App.js
│   │   │   ├── components
│   │   │   │   ├── AuthLayout
│   │   │   │   ├── CategoryInput
│   │   │   │   ├── ColorInput
│   │   │   │   ├── CurrencyInput
│   │   │   │   ├── Editor
│   │   │   │   ├── ImagePicker
│   │   │   │   ├── ListActions
│   │   │   │   ├── LoadingProgress
│   │   │   │   ├── Main
│   │   │   │   ├── MainLayout
│   │   │   │   ├── RangeDatePicker
│   │   │   │   ├── Search
│   │   │   │   └── SingleImageField
│   │   │   ├── hooks
│   │   │   │   ├── useAddress.js
│   │   │   │   ├── useAppConfig.js
│   │   │   │   ├── useAuth.js
│   │   │   │   ├── useBanks.js
│   │   │   │   ├── useListPagination.js
│   │   │   │   ├── useOrder.js
│   │   │   │   ├── useOwner.js
│   │   │   │   ├── usePriceFilter.js
│   │   │   │   └── useSetting.js
│   │   │   ├── includes
│   │   │   │   ├── ContactSetting
│   │   │   │   ├── CustomPageSetting
│   │   │   │   ├── HomePageSetting
│   │   │   │   ├── OrderExpand
│   │   │   │   ├── OrderFilter
│   │   │   │   ├── PaymentSetting
│   │   │   │   ├── PolicySetting
│   │   │   │   ├── ProductFilter
│   │   │   │   ├── ProductSetting
│   │   │   │   ├── RegisterOwnerForm
│   │   │   │   ├── SelectResourceItems
│   │   │   │   ├── SettingToolbar
│   │   │   │   └── StoreSetting
│   │   │   ├── index.css
│   │   │   ├── index.js
│   │   │   ├── language
│   │   │   │   └── vi.js
│   │   │   ├── logo.svg
│   │   │   ├── pages
│   │   │   │   ├── Appearance.jsx
│   │   │   │   ├── ChangePassword.jsx
│   │   │   │   ├── CustomPages.jsx
│   │   │   │   ├── ForgotPassword.jsx
│   │   │   │   ├── Login.jsx
│   │   │   │   ├── Payment.jsx
│   │   │   │   ├── ResetPassword.jsx
│   │   │   │   └── Setting.jsx
│   │   │   ├── providers
│   │   │   │   ├── AppProvider.js
│   │   │   │   ├── AuthProvider.js
│   │   │   │   ├── FileProvider.js
│   │   │   │   └── HttpProvider.js
│   │   │   ├── reportWebVitals.js
│   │   │   ├── resource
│   │   │   │   ├── category
│   │   │   │   ├── discounts
│   │   │   │   ├── news
│   │   │   │   ├── order
│   │   │   │   ├── product
│   │   │   │   └── user
│   │   │   └── setupTests.js
│   │   └── tailwind.config.js
│   ├── server
│   │   ├── Dockerfile
│   │   ├── Procfile
│   │   ├── ecosystem.config.js
│   │   ├── jsconfig.json
│   │   ├── package-lock.json
│   │   ├── package.json
│   │   └── src
│   │       ├── app.js
│   │       ├── assets
│   │       │   ├── forgot-password.html
│   │       │   └── order-information.html
│   │       ├── config
│   │       │   ├── constants.js
│   │       │   ├── environment.js
│   │       │   └── setting.js
│   │       ├── controllers
│   │       │   ├── auth.js
│   │       │   ├── category.js
│   │       │   ├── common.js
│   │       │   ├── discount.js
│   │       │   ├── news.js
│   │       │   ├── order.js
│   │       │   ├── product.js
│   │       │   ├── shipping.js
│   │       │   └── user.js
│   │       ├── helper
│   │       │   ├── database.js
│   │       │   └── util.js
│   │       ├── index.js
│   │       ├── middlewares
│   │       │   ├── Authorization.js
│   │       │   ├── ErrorHandler.js
│   │       │   └── RequestValidation.js
│   │       ├── mock
│   │       │   ├── data.json
│   │       │   ├── data1.json
│   │       │   ├── response.json
│   │       │   ├── response1.json
│   │       │   └── response2.json
│   │       ├── models
│   │       │   ├── category.js
│   │       │   ├── discount.js
│   │       │   ├── image.js
│   │       │   ├── news.js
│   │       │   ├── order.js
│   │       │   ├── product.js
│   │       │   ├── setting.js
│   │       │   └── user.js
│   │       ├── public
│   │       ├── routes
│   │       │   ├── auth.js
│   │       │   ├── category.js
│   │       │   ├── common.js
│   │       │   ├── discount.js
│   │       │   ├── news.js
│   │       │   ├── order.js
│   │       │   ├── product.js
│   │       │   ├── shipping.js
│   │       │   └── user.js
│   │       ├── services
│   │       │   ├── Cloudinary.js
│   │       │   ├── Mail.js
│   │       │   └── Redis.js
│   │       ├── static
│   │       ├── tasks
│   │       │   ├── category.js
│   │       │   ├── haravan.js
│   │       │   ├── parse.js
│   │       │   └── product.js
│   │       └── validations
│   │           └── index.js
│   └── web
│       ├── app
│       │   ├── [page]
│       │   │   └── page.jsx
│       │   ├── cua-hang
│       │   │   └── page.jsx
│       │   ├── don-hang
│       │   │   └── page.jsx
│       │   ├── gio-hang
│       │   │   └── page.jsx
│       │   ├── gioi-thieu
│       │   │   └── page.jsx
│       │   ├── layout.jsx
│       │   ├── not-found.jsx
│       │   ├── page.jsx
│       │   ├── san-pham
│       │   │   ├── [slug]
│       │   │   └── page.jsx
│       │   ├── sitemap.js
│       │   ├── thanh-toan
│       │   │   └── page.jsx
│       │   └── tin-tuc
│       │       ├── [slug]
│       │       └── page.jsx
│       ├── components
│       │   ├── Breadcrumb
│       │   │   └── index.jsx
│       │   ├── Button
│       │   │   └── index.jsx
│       │   ├── Carousel
│       │   │   └── index.jsx
│       │   ├── Checkbox
│       │   │   └── index.jsx
│       │   ├── ContactButtons
│       │   │   └── index.jsx
│       │   ├── Counter
│       │   │   └── index.jsx
│       │   ├── Drawer
│       │   │   └── index.jsx
│       │   ├── DrawerButton
│       │   │   └── index.jsx
│       │   ├── Footer
│       │   │   └── index.jsx
│       │   ├── GoogleAnalytics
│       │   │   └── index.jsx
│       │   ├── HTMLViewer
│       │   │   └── index.jsx
│       │   ├── Header
│       │   │   └── index.jsx
│       │   ├── Icon
│       │   │   └── index.jsx
│       │   ├── IconButton
│       │   │   └── index.jsx
│       │   ├── Image
│       │   │   └── index.jsx
│       │   ├── Input
│       │   │   └── index.jsx
│       │   ├── Lightbox
│       │   │   └── index.jsx
│       │   ├── Logo
│       │   │   └── index.jsx
│       │   ├── MenuItem
│       │   │   └── index.jsx
│       │   ├── NoDataView
│       │   │   └── index.jsx
│       │   ├── OTP
│       │   │   └── index.jsx
│       │   ├── Pagination
│       │   │   └── index.jsx
│       │   ├── RouterProgress
│       │   │   └── index.jsx
│       │   ├── ScrollTopButton
│       │   │   └── index.jsx
│       │   ├── SearchComponents
│       │   │   └── index.jsx
│       │   ├── Section
│       │   │   └── index.jsx
│       │   ├── Select
│       │   │   └── index.jsx
│       │   ├── Spinner
│       │   │   └── index.jsx
│       │   └── Steps
│       │       └── index.jsx
│       ├── config
│       │   └── Constants.js
│       ├── context
│       │   ├── AppContext.jsx
│       │   ├── CardContext.jsx
│       │   └── SettingContext.jsx
│       ├── hooks
│       │   ├── useCategories.js
│       │   ├── useDimission.js
│       │   ├── useDiscount.js
│       │   ├── useNavigation.js
│       │   ├── useNews.js
│       │   ├── useOTP.js
│       │   ├── useOrder.js
│       │   ├── usePagination.js
│       │   ├── useProducts.js
│       │   ├── useRecentIds.js
│       │   ├── useSticky.js
│       │   └── useVariants.js
│       ├── includes
│       │   ├── AddressForm
│       │   │   └── index.jsx
│       │   ├── CartButton
│       │   │   └── index.jsx
│       │   ├── CartContent
│       │   │   └── index.jsx
│       │   ├── CartDelivery
│       │   │   └── index.jsx
│       │   ├── CartItem
│       │   │   └── index.jsx
│       │   ├── CheckingOrderContent
│       │   │   └── index.jsx
│       │   ├── CheckoutContent
│       │   │   └── index.jsx
│       │   ├── CheckoutForm
│       │   │   └── index.jsx
│       │   ├── CheckoutSuccess
│       │   │   └── index.jsx
│       │   ├── ClassicHeader
│       │   │   └── index.jsx
│       │   ├── ClassicMainMenu
│       │   │   └── index.jsx
│       │   ├── CustomMenuPages
│       │   │   └── index.jsx
│       │   ├── FilterDrawer
│       │   │   └── index.jsx
│       │   ├── GradientBG
│       │   │   └── index.jsx
│       │   ├── InformationForm
│       │   │   └── index.jsx
│       │   ├── LocationItem
│       │   │   └── index.jsx
│       │   ├── MainCarousel
│       │   │   └── index.jsx
│       │   ├── MenuCategory
│       │   │   └── index.jsx
│       │   ├── MobileDrawer
│       │   │   └── index.jsx
│       │   ├── MobileMenuCategory
│       │   │   └── index.jsx
│       │   ├── ModernHeader
│       │   │   └── index.jsx
│       │   ├── ModernMainMenu
│       │   │   └── index.jsx
│       │   ├── News
│       │   │   └── index.jsx
│       │   ├── NewsHighlight
│       │   │   └── index.jsx
│       │   ├── NewsItem
│       │   │   └── index.jsx
│       │   ├── NewsLoading
│       │   │   └── index.jsx
│       │   ├── PaymentForm
│       │   │   └── index.jsx
│       │   ├── PhoneDelivery
│       │   │   └── index.jsx
│       │   ├── Policy
│       │   │   └── index.jsx
│       │   ├── ProductCarousel
│       │   │   └── index.jsx
│       │   ├── ProductFilter
│       │   │   └── index.jsx
│       │   ├── ProductGrid
│       │   │   └── index.jsx
│       │   ├── ProductInformation
│       │   │   └── index.jsx
│       │   ├── ProductItem
│       │   │   └── index.jsx
│       │   ├── ProductItemLoading
│       │   │   └── index.jsx
│       │   ├── ProductList
│       │   │   └── index.jsx
│       │   ├── ProductMeta
│       │   │   └── index.jsx
│       │   ├── ProductPromotion
│       │   │   └── index.jsx
│       │   ├── ProductSection
│       │   │   └── index.jsx
│       │   ├── ProductVariants
│       │   │   └── index.jsx
│       │   └── ShipperIcon
│       │       └── index.jsx
│       ├── jsconfig.json
│       ├── next-env.d.ts
│       ├── next.config.js
│       ├── package-lock.json
│       ├── package.json
│       ├── postcss.config.js
│       ├── public
│       │   ├── images
│       │   │   ├── facebook.png
│       │   │   ├── heat.png
│       │   │   ├── price-percent.svg
│       │   │   ├── tiktok.png
│       │   │   ├── visa.png
│       │   │   ├── vn-pay.png
│       │   │   ├── youtube.png
│       │   │   └── zalo.png
│       │   ├── next.svg
│       │   ├── robots.txt
│       │   └── vercel.svg
│       ├── services
│       │   ├── CategoryService.js
│       │   ├── CommonService.js
│       │   ├── DiscountService.js
│       │   ├── HttpService.js
│       │   ├── NewsService.js
│       │   ├── OrderService.js
│       │   ├── ProductService.js
│       │   ├── ShippingService.js
│       │   └── UtilService.js
│       ├── styles
│       │   ├── carousel.css
│       │   ├── custom.css
│       │   ├── drawer.css
│       │   ├── font.css
│       │   ├── globals.css
│       │   ├── input.css
│       │   ├── menu.css
│       │   └── text.css
│       └── tailwind.config.js
└── tree

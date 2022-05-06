//[sdk](../../index.md)/[com.swedbankpay.mobilesdk](index.md)



# Package com.swedbankpay.mobilesdk  


## Types  
  
|  Name |  Summary | 
|---|---|
| <a name="com.swedbankpay.mobilesdk/Configuration///PointingToDeclaration/"></a>[Configuration](-configuration/index.md)| <a name="com.swedbankpay.mobilesdk/Configuration///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>abstract class [Configuration](-configuration/index.md)  <br>More info  <br>The Swedbank Pay configuration for your application.  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/ConfigurationCompat///PointingToDeclaration/"></a>[ConfigurationCompat](-configuration-compat/index.md)| <a name="com.swedbankpay.mobilesdk/ConfigurationCompat///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>abstract class [ConfigurationCompat](-configuration-compat/index.md) : [Configuration](-configuration/index.md)  <br>More info  <br>Java compatibility wrapper for [Configuration](-configuration/index.md).  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/Consumer///PointingToDeclaration/"></a>[Consumer](-consumer/index.md)| <a name="com.swedbankpay.mobilesdk/Consumer///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>data class [Consumer](-consumer/index.md)(**operation**: [ConsumerOperation](-consumer-operation/index.md), **language**: [Language](-language/index.md), **shippingAddressRestrictedToCountryCodes**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>, **extensionProperties**: [Bundle](https://developer.android.com/reference/kotlin/android/os/Bundle.html)?) : [Parcelable](https://developer.android.com/reference/kotlin/android/os/Parcelable.html),   <br>More info  <br>A consumer to identify using the [checkin](https://developer.swedbankpay.com/checkout/checkin) flow.  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/ConsumerOperation///PointingToDeclaration/"></a>[ConsumerOperation](-consumer-operation/index.md)| <a name="com.swedbankpay.mobilesdk/ConsumerOperation///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>enum [ConsumerOperation](-consumer-operation/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[ConsumerOperation](-consumer-operation/index.md)>   <br>More info  <br>Operations that can be performed with a [Consumer](-consumer/index.md).  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/DeliveryTimeFrameIndicator///PointingToDeclaration/"></a>[DeliveryTimeFrameIndicator](-delivery-time-frame-indicator/index.md)| <a name="com.swedbankpay.mobilesdk/DeliveryTimeFrameIndicator///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>enum [DeliveryTimeFrameIndicator](-delivery-time-frame-indicator/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[DeliveryTimeFrameIndicator](-delivery-time-frame-indicator/index.md)>   <br>More info  <br>Product delivery timeframe for a [RiskIndicator](-risk-indicator/index.md).  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/ItemType///PointingToDeclaration/"></a>[ItemType](-item-type/index.md)| <a name="com.swedbankpay.mobilesdk/ItemType///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>enum [ItemType](-item-type/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[ItemType](-item-type/index.md)>   <br>More info  <br>The type of an [OrderItem](-order-item/index.md).  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/Language///PointingToDeclaration/"></a>[Language](-language/index.md)| <a name="com.swedbankpay.mobilesdk/Language///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>enum [Language](-language/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Language](-language/index.md)>   <br>More info  <br>Languages supported by checkin and payment menu.  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/OrderItem///PointingToDeclaration/"></a>[OrderItem](-order-item/index.md)| <a name="com.swedbankpay.mobilesdk/OrderItem///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>data class [OrderItem](-order-item/index.md)(**reference**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **type**: [ItemType](-item-type/index.md), **class**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **itemUrl**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **imageUrl**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **description**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **discountDescription**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **quantity**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **quantityUnit**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **unitPrice**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **discountPrice**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, **vatPercent**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **amount**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **vatAmount**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) : [Parcelable](https://developer.android.com/reference/kotlin/android/os/Parcelable.html)  <br>More info  <br>An item being paid for, part of a [PaymentOrder](-payment-order/index.md).  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/PayeeInfo///PointingToDeclaration/"></a>[PayeeInfo](-payee-info/index.md)| <a name="com.swedbankpay.mobilesdk/PayeeInfo///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>data class [PayeeInfo](-payee-info/index.md)(**payeeId**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **payeeReference**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **payeeName**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **productCategory**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **orderReference**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **subsite**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [Parcelable](https://developer.android.com/reference/kotlin/android/os/Parcelable.html)  <br>More info  <br>Information about the payee (recipient) of a payment order  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/PaymentFragment///PointingToDeclaration/"></a>[PaymentFragment](-payment-fragment/index.md)| <a name="com.swedbankpay.mobilesdk/PaymentFragment///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>open class [PaymentFragment](-payment-fragment/index.md) : [Fragment](https://developer.android.com/reference/kotlin/androidx/fragment/app/Fragment.html)  <br>More info  <br>A [Fragment](https://developer.android.com/reference/kotlin/androidx/fragment/app/Fragment.html) that handles a payment process.  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/PaymentInstruments///PointingToDeclaration/"></a>[PaymentInstruments](-payment-instruments/index.md)| <a name="com.swedbankpay.mobilesdk/PaymentInstruments///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>object [PaymentInstruments](-payment-instruments/index.md)  <br>More info  <br>Constant values for common payment instruments  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/PaymentOrder///PointingToDeclaration/"></a>[PaymentOrder](-payment-order/index.md)| <a name="com.swedbankpay.mobilesdk/PaymentOrder///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>data class [PaymentOrder](-payment-order/index.md)(**operation**: [PaymentOrderOperation](-payment-order-operation/index.md), **currency**: [Currency](https://developer.android.com/reference/kotlin/java/util/Currency.html), **amount**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **vatAmount**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **description**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **userAgent**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **language**: [Language](-language/index.md), **instrument**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **generateRecurrenceToken**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **generatePaymentToken**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **disableStoredPaymentDetails**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **restrictedToInstruments**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>?, **urls**: [PaymentOrderUrls](-payment-order-urls/index.md), **payeeInfo**: [PayeeInfo](-payee-info/index.md), **payer**: [PaymentOrderPayer](-payment-order-payer/index.md)?, **orderItems**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[OrderItem](-order-item/index.md)>?, **riskIndicator**: [RiskIndicator](-risk-indicator/index.md)?, **disablePaymentMenu**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **paymentToken**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **initiatingSystemUserAgent**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **extensionProperties**: [Bundle](https://developer.android.com/reference/kotlin/android/os/Bundle.html)?) : [Parcelable](https://developer.android.com/reference/kotlin/android/os/Parcelable.html),   <br>More info  <br>Description a payment order.  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/PaymentOrderOperation///PointingToDeclaration/"></a>[PaymentOrderOperation](-payment-order-operation/index.md)| <a name="com.swedbankpay.mobilesdk/PaymentOrderOperation///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>enum [PaymentOrderOperation](-payment-order-operation/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[PaymentOrderOperation](-payment-order-operation/index.md)>   <br>More info  <br>Type of operation the payment order performs  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/PaymentOrderPayer///PointingToDeclaration/"></a>[PaymentOrderPayer](-payment-order-payer/index.md)| <a name="com.swedbankpay.mobilesdk/PaymentOrderPayer///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>data class [PaymentOrderPayer](-payment-order-payer/index.md)(**consumerProfileRef**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **email**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **msisdn**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **payerReference**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [Parcelable](https://developer.android.com/reference/kotlin/android/os/Parcelable.html)  <br>More info  <br>Information about the payer of a payment order  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/PaymentOrderUrls///PointingToDeclaration/"></a>[PaymentOrderUrls](-payment-order-urls/index.md)| <a name="com.swedbankpay.mobilesdk/PaymentOrderUrls///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>data class [PaymentOrderUrls](-payment-order-urls/index.md)(**hostUrls**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>, **completeUrl**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **cancelUrl**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **paymentUrl**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **callbackUrl**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **termsOfServiceUrl**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [Parcelable](https://developer.android.com/reference/kotlin/android/os/Parcelable.html)  <br>More info  <br>A set of URLs relevant to a payment order.  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/PaymentViewModel///PointingToDeclaration/"></a>[PaymentViewModel](-payment-view-model/index.md)| <a name="com.swedbankpay.mobilesdk/PaymentViewModel///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>class [PaymentViewModel](-payment-view-model/index.md) : [AndroidViewModel](https://developer.android.com/reference/kotlin/androidx/lifecycle/AndroidViewModel.html)  <br>More info  <br><a href="https://developer.android.  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/PickUpAddress///PointingToDeclaration/"></a>[PickUpAddress](-pick-up-address/index.md)| <a name="com.swedbankpay.mobilesdk/PickUpAddress///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>data class [PickUpAddress](-pick-up-address/index.md)(**name**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **streetAddress**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **coAddress**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **city**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **zipCode**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **countryCode**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) : [Parcelable](https://developer.android.com/reference/kotlin/android/os/Parcelable.html)  <br>More info  <br>Pick-up address data for [RiskIndicator](-risk-indicator/index.md).  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/PreOrderPurchaseIndicator///PointingToDeclaration/"></a>[PreOrderPurchaseIndicator](-pre-order-purchase-indicator/index.md)| <a name="com.swedbankpay.mobilesdk/PreOrderPurchaseIndicator///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>enum [PreOrderPurchaseIndicator](-pre-order-purchase-indicator/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[PreOrderPurchaseIndicator](-pre-order-purchase-indicator/index.md)>   <br>More info  <br>Purchase indicator values for [RiskIndicator](-risk-indicator/index.md).  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/Problem///PointingToDeclaration/"></a>[Problem](-problem/index.md)| <a name="com.swedbankpay.mobilesdk/Problem///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>open class [Problem](-problem/index.md) : [Parcelable](https://developer.android.com/reference/kotlin/android/os/Parcelable.html), [Serializable](https://developer.android.com/reference/kotlin/java/io/Serializable.html)  <br>More info  <br>An RFC 7807 HTTP API Problem Details object.  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/ReOrderPurchaseIndicator///PointingToDeclaration/"></a>[ReOrderPurchaseIndicator](-re-order-purchase-indicator/index.md)| <a name="com.swedbankpay.mobilesdk/ReOrderPurchaseIndicator///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>enum [ReOrderPurchaseIndicator](-re-order-purchase-indicator/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[ReOrderPurchaseIndicator](-re-order-purchase-indicator/index.md)>   <br>More info  <br>Re-order purchase indicator values for [RiskIndicator](-risk-indicator/index.md).  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/RequestDecorator///PointingToDeclaration/"></a>[RequestDecorator](-request-decorator/index.md)| <a name="com.swedbankpay.mobilesdk/RequestDecorator///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>abstract class [RequestDecorator](-request-decorator/index.md)  <br>More info  <br>Callback for adding custom headers to backend requests.  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/RequestDecoratorCompat///PointingToDeclaration/"></a>[RequestDecoratorCompat](-request-decorator-compat/index.md)| <a name="com.swedbankpay.mobilesdk/RequestDecoratorCompat///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>@[WorkerThread](https://developer.android.com/reference/kotlin/androidx/annotation/WorkerThread.html)()  <br>  <br>open class [RequestDecoratorCompat](-request-decorator-compat/index.md) : [RequestDecorator](-request-decorator/index.md)  <br>More info  <br>Java compatibility wrapper for [RequestDecorator](-request-decorator/index.md).  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/RiskIndicator///PointingToDeclaration/"></a>[RiskIndicator](-risk-indicator/index.md)| <a name="com.swedbankpay.mobilesdk/RiskIndicator///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>data class [RiskIndicator](-risk-indicator/index.md)(**deliveryEmailAddress**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **deliveryTimeFrameIndicator**: [DeliveryTimeFrameIndicator](-delivery-time-frame-indicator/index.md)?, **preOrderDate**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **preOrderPurchaseIndicator**: [PreOrderPurchaseIndicator](-pre-order-purchase-indicator/index.md)?, **shipIndicator**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **pickUpAddress**: [PickUpAddress](-pick-up-address/index.md)?, **giftCardPurchase**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, **reOrderPurchaseIndicator**: [ReOrderPurchaseIndicator](-re-order-purchase-indicator/index.md)?) : [Parcelable](https://developer.android.com/reference/kotlin/android/os/Parcelable.html)  <br>More info  <br>Optional information to reduce the risk factor of a payment.  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/ShipIndicator///PointingToDeclaration/"></a>[ShipIndicator](-ship-indicator/index.md)| <a name="com.swedbankpay.mobilesdk/ShipIndicator///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>class [ShipIndicator](-ship-indicator/index.md)  <br>More info  <br>Shipping method for [RiskIndicator](-risk-indicator/index.md).  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/TerminalFailure///PointingToDeclaration/"></a>[TerminalFailure](-terminal-failure/index.md)| <a name="com.swedbankpay.mobilesdk/TerminalFailure///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>class [TerminalFailure](-terminal-failure/index.md) : [Parcelable](https://developer.android.com/reference/kotlin/android/os/Parcelable.html)  <br>More info  <br>Describes a terminal error condition signaled by an onError callback from Swedbank Pay.  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/UserHeaders///PointingToDeclaration/"></a>[UserHeaders](-user-headers/index.md)| <a name="com.swedbankpay.mobilesdk/UserHeaders///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>class [UserHeaders](-user-headers/index.md)  <br>More info  <br>Builder for custom headers.  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/ViewConsumerIdentificationInfo///PointingToDeclaration/"></a>[ViewConsumerIdentificationInfo](-view-consumer-identification-info/index.md)| <a name="com.swedbankpay.mobilesdk/ViewConsumerIdentificationInfo///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>data class [ViewConsumerIdentificationInfo](-view-consumer-identification-info/index.md)(**webViewBaseUrl**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **viewConsumerIdentification**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br>More info  <br>Data required to show the checkin view.  <br><br><br>|
| <a name="com.swedbankpay.mobilesdk/ViewPaymentOrderInfo///PointingToDeclaration/"></a>[ViewPaymentOrderInfo](-view-payment-order-info/index.md)| <a name="com.swedbankpay.mobilesdk/ViewPaymentOrderInfo///PointingToDeclaration/"></a>[androidJvm]  <br>Content  <br>data class [ViewPaymentOrderInfo](-view-payment-order-info/index.md)(**webViewBaseUrl**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **viewPaymentOrder**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **completeUrl**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **cancelUrl**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **paymentUrl**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **termsOfServiceUrl**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **instrument**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, **availableInstruments**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>?, **userData**: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?) : [Parcelable](https://developer.android.com/reference/kotlin/android/os/Parcelable.html)  <br>More info  <br>Data required to show the payment menu.  <br><br><br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="com.swedbankpay.mobilesdk//paymentViewModel/androidx.fragment.app.FragmentActivity#/PointingToDeclaration/"></a>[paymentViewModel](payment-view-model.md)| <a name="com.swedbankpay.mobilesdk//paymentViewModel/androidx.fragment.app.FragmentActivity#/PointingToDeclaration/"></a> [androidJvm] val [FragmentActivity](https://developer.android.com/reference/kotlin/androidx/fragment/app/FragmentActivity.html).[paymentViewModel](payment-view-model.md): [PaymentViewModel](-payment-view-model/index.md)Convenience for ViewModelProvider(activity).get(PaymentViewModel::class.java).   <br>|

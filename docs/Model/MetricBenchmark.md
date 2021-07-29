# # MetricBenchmark

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**adjustment** | **string** | If this field is present, it indicates that the rating given to the seller was &amp;quot;adjusted&amp;quot; for one reason or another. If eBay determines that the normal rating of a seller is impacted by circumstances beyond their control, they can issue an override to adjust the rating given to the seller. For implementation help, refer to &lt;a href&#x3D;&#39;https://developer.ebay.com/api-docs/sell/analytics/types/api:RatingAdjustmentTypeEnum&#39;&gt;eBay API documentation&lt;/a&gt; | [optional]
**basis** | **string** | This field returns the &amp;quot;basis&amp;quot; by which the benchmark is calculated for the customer service metric type. Currently, the only supported basis is PEER_BENCHMARK. For implementation help, refer to &lt;a href&#x3D;&#39;https://developer.ebay.com/api-docs/sell/analytics/types/api:BenchmarkTypeEnum&#39;&gt;eBay API documentation&lt;/a&gt; | [optional]
**metadata** | [**\Ebay\Sell\Analytics\Model\BenchmarkMetadata**](BenchmarkMetadata.md) |  | [optional]
**rating** | **string** | This field returns seller&#39;s rating for the customer service metric. The rating is set to a value that equals the relative deviation between the seller&#39;s metric value and the benchmark value for the customer service metric. Deviation values range from LOW to VERY HIGH, and the lower the deviation, the better the seller rating. For implementation help, refer to &lt;a href&#x3D;&#39;https://developer.ebay.com/api-docs/sell/analytics/types/api:RatingTypeEnum&#39;&gt;eBay API documentation&lt;/a&gt; | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)

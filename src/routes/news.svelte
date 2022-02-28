<script>
	import NewsItem from '$lib/news/news-item.svelte';
</script>

<section class="py-24 bg-white overflow-hidden">
	<div class="position-relative container">
		<img
			class="position-absolute top-0 start-0 mt-n44 ms-n60"
			src="pstls-assets/images/call-to-action/shadows-big.png"
			alt=""
		/>
		<div class="position-relative">
			<div class="row align-items-md-center">
				<div class="col-12 col-md-5 mb-6 mb-md-0">
					<h1 class="mb-0 lh-sm font-heading">Notícias</h1>
				</div>
				<div class="col-12 col-md-7">
					<p class="mb-0 lh-lg">
						If you have ever wondered how to develop your brand, this is the place for you. Take a
						big step forward in growing your business with this great tool.
					</p>
				</div>
			</div>
		</div>
		<div class="row align-items-md-center mt-8 mt-xl-12">
			<NewsItem title="Lorem Ipsum" image="/pstls-assets/images/features/features-6-room.png">
				If you have ever wondered how to develop your brand, this is the place for you. Take a big
				step forward in growing your business with this great tool...
			</NewsItem>
			<NewsItem title="Lorem Ipsum" image="/pstls-assets/images/features/features-6-room.png">
				If you have ever wondered how to develop your brand, this is the place for you. Take a big
				step forward in growing your business with this great tool...
			</NewsItem>
			<NewsItem title="Lorem Ipsum" image="/pstls-assets/images/features/features-6-room.png">
				If you have ever wondered how to develop your brand, this is the place for you. Take a big
				step forward in growing your business with this great tool...
			</NewsItem>
		</div>
	</div>
</section>

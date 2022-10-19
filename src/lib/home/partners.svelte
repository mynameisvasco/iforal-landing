<script>
	import { language } from '$lib/language';
</script>

<section class="position-relative">
	<div class="pt-12 border-bottom pb-24">
		<div class="container">
			<div class="row">
				<div class="col-6">
					<p class="lh-lg text-center text-muted">
						{$language === 'pt' ? 'Instituições de acolhimento' : 'Host institutions'}
					</p>
					<div class="col-12 text-center mb-md-0">
						<img
							class="img-fluid d-block "
							style="width: 100%;"
							src="https://i.imgur.com/z8ow2Hn.png"
							alt=""
						/>
					</div>
				</div>
				<div class="col-6">
					<p class="lh-lg text-center text-muted">
						{$language === 'pt' ? 'Instituições participantes' : 'Participating institutions'}
					</p>
					<div class="row align-items-center">
						<div class="col-12 text-center mb-md-0">
							<img
								class="img-fluid d-block "
								style="width: 100%;"
								src="https://i.imgur.com/Mtsj5q1.png"
								alt=""
							/>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
	<div class="pt-12">
		<div class="container">
			<p class="lh-lg text-center text-muted">
				{$language === 'pt' ? 'Parceiros principais' : 'Main partners'}
			</p>
			<div class="row align-items-center">
				<div class="col-12 text-center mb-md-0">
					<img
						class="img-fluid d-block mx-auto px-24"
						style="max-width: 800px"
						src="https://i.imgur.com/15dfjch.png"
						alt=""
					/>
				</div>
			</div>
		</div>
	</div>
	<div class="position-absolute top-0 start-0 px-1 bg-danger-light" />
	<div class="position-absolute bottom-0 end-0 px-1 bg-danger-light" />
</section>

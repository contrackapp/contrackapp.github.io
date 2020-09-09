---
layout: default
title: Home
---

<div class="w-full">
	<div class="flex flex-col justify-center items-center">
		<div class="my-2">
			<img class="w-32 h-32" src="{{ site.data.manifest['images/logo.png'] }}" />
		</div>	
		<h3 class="roboto text-gray-700 font-bold" style="font-size: 22px;">
			Welcome to CONTRACK
		</h3>
		<h6 class="montserrat text-gray-600 mt-2" style="font-size: 13px;">
			Scan, share, and create your contacts
		</h6>
		<a href="{{ site.download_android }}" class="mt-5 px-4 py-2 bg-blue-600 text-blue-200 rounded-lg">
			Download for Android (Version {{ site.app_version }})
		</a>
	</div>
	<div class="flex flex-col items-center justify-center mt-10">
		<h4 class="roboto font-bold text-gray-700" style="font-size: 17px;">APPLICATION FEATURES</h4>
		<div class="flex flex-col sm:flex-row items-center justify-center w-1/2 border-b pb-2 border-gray-400">
			<img class="w-full sm:w-32 h-30" src="{{ site.data.manifest['images/vector/qr_scan.png'] }}" />
			<div class="sm:ml-10">
				<p class="montserrat text-justify text-gray-700 font-light sm:m-10" style="font-size: 14px;">Ask them for the <strong class="font-bold roboto">Contrack QR</strong> and scan it using your Contrack App. Voila! You have logged in your app that person/establishment and the date and time of contact</p>
			</div>
		</div>
		<div class="flex flex-col sm:flex-row items-center justify-center w-1/2 border-b pb-2 border-gray-400 my-4">
				<img class="w-full sm:w-32 h-30" src="{{ site.data.manifest['images/vector/add_contact.png'] }}" />
			<div class="sm:ml-10">
				<p class="montserrat text-justify text-gray-700 font-light sm:m-10" style="font-size: 14px;">No <strong class="font-bold roboto">Contrack QR</strong>? Worry no more. You can also manually add your contacts</p>
			</div>
		</div>
		<div class="flex flex-col sm:flex-row items-center justify-center w-1/2">
				<img class="w-full sm:w-32 h-30" src="{{ site.data.manifest['images/vector/scan_and_share.png'] }}" />
			<div class="sm:ml-10">
				<p class="montserrat text-justify text-gray-700 font-light sm:m-10" style="font-size: 14px;">No more hassle writing of contact information. Generate your own <strong class="font-bold roboto">Contrack QR</strong> and let another person/establishments scan it using their Contrack App.</p>
			</div>
		</div>
	</div>
	<div class="flex flex-col justify-center items-center mt-5">
		<h4 class="roboto font-bold text-gray-700" style="font-size: 17px;">SCREENSHOTS</h4>
		<div class="flex flex-row mt-8">
			<img class="w-32 mr-2" src="{{ site.data.manifest['images/contact_list-min.jpg'] }}" />
			<img class="w-32 mr-2" src="{{ site.data.manifest['images/fillup-min.jpg'] }}" />
			<img class="w-32" src="{{ site.data.manifest['images/scan-min.jpg'] }}" />
		</div>	
	</div>
	<div class="py-10 mt-10 bg-gray-200 w-full flex flex-row justify-center items-center">
		<p class="montserrat w-1/2 text-center" style="font-size: 15px;">Find any bugs? Have any suggestions and comments? Email us your experience with our application at <strong class="font-bold roboto">{{ site.email }}</strong></p>
	</div>
	<div class="py-2 bg-gray-700 w-full flex flex-row justify-center items-center">
		<p class="roboto w-1/2 text-gray-200 text-center" style="font-size: 10px;">© May 2020</p>
	</div>
</div>
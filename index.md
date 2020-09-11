---
layout: default
title: Home
---

<div class="w-full">
	<div class="flex flex-col justify-center items-center">
		<div class="mb-2">
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
	<div class="flex flex-col items-center justify-center mt-10 px-5">
		<h4 class="roboto font-bold text-gray-700" style="font-size: 17px;">APPLICATION FEATURES</h4>
		<div class="flex flex-col sm:flex-row items-center justify-center sm:w-1/2 border-b pb-2 border-gray-400">
			<img class="w-full sm:w-32 h-30" src="{{ site.data.manifest['images/vector/qr_scan.png'] }}" />
			<div class="sm:ml-10">
				<p class="montserrat text-justify text-gray-700 font-light sm:m-10" style="font-size: 14px;">Ask for the <strong class="font-bold roboto">Contrack QR Code</strong> and scan it using the app. Contact tracking made easy and convenient for the people and establishments by tracking down the place, date and time of contact.</p>
			</div>
		</div>
		<div class="flex flex-col sm:flex-row items-center justify-center sm:w-1/2 border-b pb-2 border-gray-400 my-4">
				<img class="w-full sm:w-32 h-30" src="{{ site.data.manifest['images/vector/add_contact.png'] }}" />
			<div class="sm:ml-10">
				<p class="montserrat text-justify text-gray-700 font-light sm:m-10" style="font-size: 14px;">Others doesn't have <strong class="font-bold roboto">Contrack QR Code</strong>? Worry no more. Manually add the information on your contacts.</p>
			</div>
		</div>
		<div class="flex flex-col sm:flex-row items-center justify-center sm:w-1/2">
				<img class="w-full sm:w-32 h-30" src="{{ site.data.manifest['images/vector/scan_and_share.png'] }}" />
			<div class="sm:ml-10">
				<p class="montserrat text-justify text-gray-700 font-light sm:m-10" style="font-size: 14px;">Less hassle writing of contact information. Generate a <strong class="font-bold roboto">Contrack QR Code</strong>, and let other person and establishments in contact scan it using their Contrack App.</p>
			</div>
		</div>
	</div>
</div>
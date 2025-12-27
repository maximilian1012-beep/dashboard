# dashboard
Saldo vendor


<html lang="en">
  <head>
    <meta charset="utf-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover"/>
    <meta http-equiv="X-UA-Compatible" content="ie=edge"/>
    <title>Merchant Panel Tiers Status
</title>
    <!-- CSS files -->
	<link href="https://dashboard.q2checkout.com/template/tabler/dist/css/tabler.min.css" rel="stylesheet"/>
    <link href="https://dashboard.q2checkout.com/template/tabler/dist/css/tabler-flags.min.css" rel="stylesheet"/>
    <link href="https://dashboard.q2checkout.com/template/tabler/dist/css/tabler-payments.min.css" rel="stylesheet"/>
    <link href="https://dashboard.q2checkout.com/template/tabler/dist/css/tabler-vendors.min.css" rel="stylesheet"/>
	<link href="https://dashboard.q2checkout.com/addons/datatables_bs4/datatables_bs4.min.css" rel="stylesheet"/>
	<link href="https://dashboard.q2checkout.com/addons/bootstrap-multiselect/css/bootstrap-multiselect.css" rel="stylesheet">
	<style>
      @import url('https://rsms.me/inter/inter.css');
      :root {
      	--tblr-font-sans-serif: 'Inter Var', -apple-system, BlinkMacSystemFont, San Francisco, Segoe UI, Roboto, Helvetica Neue, sans-serif;
      }
      body {
      	font-feature-settings: "cv03", "cv04", "cv11";
      }
    </style>
	    <link href="https://dashboard.q2checkout.com/assets/css/backend.css" rel="stylesheet"/>
  </head>
<body class="antialiased ">
	<div class="page">

		<!-- Header -->
		<header class="navbar navbar-expand-md d-print-none header-top-primary">
		<div class="container-fluid">
		  <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbar-menu" aria-controls="navbar-menu" aria-expanded="false" aria-label="Toggle navigation">
			<span class="navbar-toggler-icon"></span>
		  </button>
		  <h1 class="navbar-brand navbar-brand-autodark d-none-navbar-horizontal pe-0 pe-md-3">
			<a href="https://dashboard.q2checkout.com/~admin99">
			Merchant Panel
			</a>
		  </h1>

		 <div class="navbar-nav flex-row order-md-last">
			<div class="d-none d-md-flex">
			  <a href="https://dashboard.q2checkout.com/panel" class="nav-link px-0 hide-theme-dark" title="Dashboard" target="_dashboard">

				<svg  xmlns="http://www.w3.org/2000/svg"  width="24"  height="24"  viewBox="0 0 24 24"  fill="none"  stroke="currentColor"  stroke-width="2"  stroke-linecap="round"  stroke-linejoin="round"  class="icon icon-tabler icons-tabler-outline icon-tabler-plane-tilt"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M14.5 6.5l3 -2.9a2.05 2.05 0 0 1 2.9 2.9l-2.9 3l2.5 7.5l-2.5 2.55l-3.5 -6.55l-3 3v3l-2 2l-1.5 -4.5l-4.5 -1.5l2 -2h3l3 -3l-6.5 -3.5l2.5 -2.5l7.5 2.5z" /></svg> &nbsp;
				<i>Client Dashboard</i>

			  </a> &nbsp;&nbsp;
			  <a href="?theme=dark" class="nav-link px-0 hide-theme-dark" title="Enable dark mode" data-bs-toggle="tooltip"
		   data-bs-placement="bottom">
				<!-- Download SVG icon from http://tabler-icons.io/i/moon -->
				<svg xmlns="http://www.w3.org/2000/svg" class="icon" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M12 3c.132 0 .263 0 .393 0a7.5 7.5 0 0 0 7.92 12.446a9 9 0 1 1 -8.313 -12.454z" /></svg>
			  </a>
			  <a href="?theme=light" class="nav-link px-0 hide-theme-light" title="Enable light mode" data-bs-toggle="tooltip"
		   data-bs-placement="bottom">
				<!-- Download SVG icon from http://tabler-icons.io/i/sun -->
				<svg xmlns="http://www.w3.org/2000/svg" class="icon" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M12 12m-4 0a4 4 0 1 0 8 0a4 4 0 1 0 -8 0" /><path d="M3 12h1m8 -9v1m8 8h1m-9 8v1m-6.4 -15.4l.7 .7m12.1 -.7l-.7 .7m0 11.4l.7 .7m-12.1 -.7l-.7 .7" /></svg>
			  </a>
			  <div class="nav-item dropdown d-none d-md-flex me-3">
				<a href="#" class="nav-link px-0" data-bs-toggle="dropdown" tabindex="-1" aria-label="Show notifications">
				  <!-- Download SVG icon from http://tabler-icons.io/i/bell -->
				  <svg xmlns="http://www.w3.org/2000/svg" class="icon" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M10 5a2 2 0 1 1 4 0a7 7 0 0 1 4 6v3a4 4 0 0 0 2 3h-16a4 4 0 0 0 2 -3v-3a7 7 0 0 1 4 -6" /><path d="M9 17v1a3 3 0 0 0 6 0v-1" /></svg>
				  <span class="badge bg-red"></span>
				</a>
				<div class="dropdown-menu dropdown-menu-arrow dropdown-menu-end dropdown-menu-card">
					 <div class="card">
						<div class="card-header">
						  <h3 class="card-title">Last updates</h3>
						</div>
						<div class="list-group list-group-flush list-group-hoverable">
						<div class="list-group-item">
		<div class="row align-items-center">
		  <div class="col-auto"><span class="status-dot status-dot-animated bg-red d-block"></span></div>
		  <div class="col text-truncate">
			<a href="#" class="text-body d-block">Example 1</a>
			<div class="d-block text-muted text-truncate mt-n1">
			  Change deprecated html tags to text decoration classes (#29604)
			</div>
		  </div>
		  <div class="col-auto">
			<a href="#" class="list-group-item-actions">
			  <!-- Download SVG icon from http://tabler-icons.io/i/star -->
			  <svg xmlns="http://www.w3.org/2000/svg" class="icon text-muted" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" /></svg>
			</a>
		  </div>
		</div>
	  </div>
	  <div class="list-group-item">
		<div class="row align-items-center">
		  <div class="col-auto"><span class="status-dot d-block"></span></div>
		  <div class="col text-truncate">
			<a href="#" class="text-body d-block">Example 2</a>
			<div class="d-block text-muted text-truncate mt-n1">
			  justify-content:between ⇒ justify-content:space-between (#29734)
			</div>
		  </div>
		  <div class="col-auto">
			<a href="#" class="list-group-item-actions show">
			  <!-- Download SVG icon from http://tabler-icons.io/i/star -->
			  <svg xmlns="http://www.w3.org/2000/svg" class="icon text-yellow" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" /></svg>
			</a>
		  </div>
		</div>
	  </div>
	  <div class="list-group-item">
		<div class="row align-items-center">
		  <div class="col-auto"><span class="status-dot d-block"></span></div>
		  <div class="col text-truncate">
			<a href="#" class="text-body d-block">Example 3</a>
			<div class="d-block text-muted text-truncate mt-n1">
			  Update change-version.js (#29736)
			</div>
		  </div>
		  <div class="col-auto">
			<a href="#" class="list-group-item-actions">
			  <!-- Download SVG icon from http://tabler-icons.io/i/star -->
			  <svg xmlns="http://www.w3.org/2000/svg" class="icon text-muted" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" /></svg>
			</a>
		  </div>
		</div>
	  </div>
	  <div class="list-group-item">
		<div class="row align-items-center">
		  <div class="col-auto"><span class="status-dot status-dot-animated bg-green d-block"></span></div>
		  <div class="col text-truncate">
			<a href="#" class="text-body d-block">Example 4</a>
			<div class="d-block text-muted text-truncate mt-n1">
			  Regenerate package-lock.json (#29730)
			</div>
		  </div>
		  <div class="col-auto">
			<a href="#" class="list-group-item-actions">
			  <!-- Download SVG icon from http://tabler-icons.io/i/star -->
			  <svg xmlns="http://www.w3.org/2000/svg" class="icon text-muted" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" /></svg>
			</a>
		  </div>
		</div>
	  </div>


						</div>
					</div>
				</div>
			  </div>
			</div>
			<div class="nav-item dropdown">
			  <a href="#" class="nav-link d-flex lh-1 text-reset p-0" data-bs-toggle="dropdown" aria-label="Open user menu">	
				<div class="d-none d-xl-block ps-2">
					<div>balanceviewer1b2b</div>
					<div class="mt-1 small text-muted"></div>
				</div>
			  </a>
			  <div class="dropdown-menu dropdown-menu-end dropdown-menu-arrow">
			   <!-- <a href="#" class="dropdown-item">Set status</a> -->
				<a href="https://dashboard.q2checkout.com/~admin99/profile" class="dropdown-item">Profile</a>
				<!-- <a href="#" class="dropdown-item">Feedback</a> -->
				<div class="dropdown-divider"></div>
				<!-- <a href="#" class="dropdown-item">Settings</a> -->
				<a href="https://dashboard.q2checkout.com/~admin99/logout" class="dropdown-item">Logout</a>
			  </div>
			</div>
		  </div>


		  <div class="collapse navbar-collapse" id="navbar-menu">
			<div class="d-flex flex-column flex-md-row flex-fill align-items-stretch align-items-md-center">
			 <ul class="navbar-nav">

				<li class="nav-item   ">
				  <a class="nav-link" href="https://dashboard.q2checkout.com/~admin99" >
					<span class="nav-link-icon d-md-none d-lg-inline-block"><svg xmlns="http://www.w3.org/2000/svg" class="icon" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><polyline points="5 12 3 12 12 3 21 12 19 12" /><path d="M5 12v7a2 2 0 0 0 2 2h10a2 2 0 0 0 2 -2v-7" /><path d="M9 21v-6a2 2 0 0 1 2 -2h2a2 2 0 0 1 2 2v6" /></svg>
					</span>
					<span class="nav-link-title">
					  Home
					</span>
				  </a>
				</li>



				<li class="nav-item dropdown ">
					<a class="nav-link dropdown-toggle" href="#navbar-extra" data-bs-toggle="dropdown" role="button" aria-expanded="false">
						<span class="nav-link-icon d-md-none d-lg-inline-block">
							<svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-building-factory-2" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M3 21h18" /><path d="M5 21v-12l5 4v-4l5 4h4" /><path d="M19 21v-8l-1.436 -9.574a.5 .5 0 0 0 -.495 -.426h-1.145a.5 .5 0 0 0 -.494 .418l-1.43 8.582" /><path d="M9 17h1" /><path d="M14 17h1" /></svg>
						</span>
						<span class="nav-link-title"> PGA </span>
					</a>
					<div class="dropdown-menu">
						<a class="dropdown-item" href="https://dashboard.q2checkout.com/~admin99/pga.status">PGA Status</a>
					</div>
				</li>









			  </ul>


		   </div>
		  </div>
		</div>
		</header>
		<!-- End: Header -->




		 <div class="page-wrapper">

		   <!-- Page header -->
		   			<div class="page-header d-print-none">
			  <div class="container-fluid">
				<div class="row g-2 align-items-center">
				  <div class="col">
					<div class="page-pretitle">
						
					</div>
					<h2 class="page-title">
					  Tiers Status
					</h2>
				  </div>

					<!-- Page title actions -->
					<div class="col-auto ms-auto d-print-none">
						<div class="btn-list">
						  <a href="https://dashboard.q2checkout.com/~admin99/merchant" class="btn btn-primary d-none d-sm-inline-block" >Back</a>
						</div>
					</div>
					<!-- End: Page title actions -->

				</div>
			  </div>
			</div>
			
			<!-- Page body -->
			<div class="page-body">
			  <div class="container-fluid">
				<!-- Content here -->

					<!-- Show/Error message -->
					<div id="ajxForm_message"></div>
					
										
					


	
		
				<div class="row">
			<div class="col-12">
				<div class="card">
				<div class="card-header">
					<h3 class="card-title">B2B - TIER0 | https://api0.securepayment.online</h3>
				</div>
				<div class="card-body">
					<div class="table">
						<table class="table table-striped card-table table-vcenter text-nowrap">
							<thead>
								<tr>
									<th width="250">PGA</th>
									<th width="350">URL</th>
									<th>PANEL STATUS</th>
									<th>IN-LB STATUS</th>
									<th>API PAYMENT SERVICE STATUS</th>
									<th>API DISBURSEMENT SERVICE STATUS</th>
																		<th>PGA ONLINE STATUS</th>
																		<th class="text-end">PGA VENDOR BALANCE</th>
								</tr>
							</thead>
							<tbody>
																<tr>
									<td>ORDER2</td>
									<td>https://order2.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=82" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>ORDER3</td>
									<td>https://order3.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=31" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>ORDER5</td>
									<td>https://order5.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=50" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>ORDER6</td>
									<td>https://order6.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=64" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>ORDER7</td>
									<td>https://order7.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=67" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>ORDER8</td>
									<td>https://order8.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=90" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>ORDER9</td>
									<td>https://order9.bebasbayar.click</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=91" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
															</tbody>
						</table>
					</div>
				</div>
				</div>
			</div>
		</div>
		<br />
				
				<div class="row">
			<div class="col-12">
				<div class="card">
				<div class="card-header">
					<h3 class="card-title">B2B - TIER1 | https://api1.securepayment.online</h3>
				</div>
				<div class="card-body">
					<div class="table">
						<table class="table table-striped card-table table-vcenter text-nowrap">
							<thead>
								<tr>
									<th width="250">PGA</th>
									<th width="350">URL</th>
									<th>PANEL STATUS</th>
									<th>IN-LB STATUS</th>
									<th>API PAYMENT SERVICE STATUS</th>
									<th>API DISBURSEMENT SERVICE STATUS</th>
																		<th>PGA ONLINE STATUS</th>
																		<th class="text-end">PGA VENDOR BALANCE</th>
								</tr>
							</thead>
							<tbody>
																<tr>
									<td>PAYMENT21</td>
									<td>https://payment21.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=56" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>PAYMENT4</td>
									<td>https://payment4.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=53" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>PAYMENT5</td>
									<td>https://payment5.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=70" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>PAYMENT6</td>
									<td>https://payment6.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=87" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
															</tbody>
						</table>
					</div>
				</div>
				</div>
			</div>
		</div>
		<br />
				
				<div class="row">
			<div class="col-12">
				<div class="card">
				<div class="card-header">
					<h3 class="card-title">B2B - TIER2 | https://api2.securepayment.online</h3>
				</div>
				<div class="card-body">
					<div class="table">
						<table class="table table-striped card-table table-vcenter text-nowrap">
							<thead>
								<tr>
									<th width="250">PGA</th>
									<th width="350">URL</th>
									<th>PANEL STATUS</th>
									<th>IN-LB STATUS</th>
									<th>API PAYMENT SERVICE STATUS</th>
									<th>API DISBURSEMENT SERVICE STATUS</th>
																		<th>PGA ONLINE STATUS</th>
																		<th class="text-end">PGA VENDOR BALANCE</th>
								</tr>
							</thead>
							<tbody>
																<tr>
									<td>CHECKOUT1</td>
									<td>https://checkout1.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=6" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>CHECKOUT31</td>
									<td>https://checkout31.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=58" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>CHECKOUT4</td>
									<td>https://checkout4.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=51" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>CHECKOUT5</td>
									<td>https://checkout5.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=71" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>CHECKOUT6</td>
									<td>https://checkout6.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=85" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>CHECKOUT7</td>
									<td>https://checkout7.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=89" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
															</tbody>
						</table>
					</div>
				</div>
				</div>
			</div>
		</div>
		<br />
				
				<div class="row">
			<div class="col-12">
				<div class="card">
				<div class="card-header">
					<h3 class="card-title">B2B - TIER3 | https://api3.securepayment.online</h3>
				</div>
				<div class="card-body">
					<div class="table">
						<table class="table table-striped card-table table-vcenter text-nowrap">
							<thead>
								<tr>
									<th width="250">PGA</th>
									<th width="350">URL</th>
									<th>PANEL STATUS</th>
									<th>IN-LB STATUS</th>
									<th>API PAYMENT SERVICE STATUS</th>
									<th>API DISBURSEMENT SERVICE STATUS</th>
																		<th>PGA ONLINE STATUS</th>
																		<th class="text-end">PGA VENDOR BALANCE</th>
								</tr>
							</thead>
							<tbody>
																<tr>
									<td>SETTLE1</td>
									<td>https://settle1.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=9" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>SETTLE2</td>
									<td>https://settle2.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=10" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>SETTLE31</td>
									<td>https://settle31.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=55" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>SETTLE4</td>
									<td>https://settle4.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=52" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>SETTLE5</td>
									<td>https://settle5.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=72" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>SETTLE6</td>
									<td>https://settle6.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=93" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
															</tbody>
						</table>
					</div>
				</div>
				</div>
			</div>
		</div>
		<br />
				
				<div class="row">
			<div class="col-12">
				<div class="card">
				<div class="card-header">
					<h3 class="card-title">B2B - VIP1 | https://api4.securepayment.online</h3>
				</div>
				<div class="card-body">
					<div class="table">
						<table class="table table-striped card-table table-vcenter text-nowrap">
							<thead>
								<tr>
									<th width="250">PGA</th>
									<th width="350">URL</th>
									<th>PANEL STATUS</th>
									<th>IN-LB STATUS</th>
									<th>API PAYMENT SERVICE STATUS</th>
									<th>API DISBURSEMENT SERVICE STATUS</th>
																		<th>PGA ONLINE STATUS</th>
																		<th class="text-end">PGA VENDOR BALANCE</th>
								</tr>
							</thead>
							<tbody>
																<tr>
									<td>SECURE10</td>
									<td>https://secure10.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=45" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>SECURE11</td>
									<td>https://secure11.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=68" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>SECURE12</td>
									<td>https://secure12.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=73" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>SECURE31</td>
									<td>https://secure31.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=59" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>SECURE6</td>
									<td>https://secure6.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=34" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>SECURE9</td>
									<td>https://secure9.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=40" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
															</tbody>
						</table>
					</div>
				</div>
				</div>
			</div>
		</div>
		<br />
				
				<div class="row">
			<div class="col-12">
				<div class="card">
				<div class="card-header">
					<h3 class="card-title">B2B - VIP1B | https://api4b.securepayment.online</h3>
				</div>
				<div class="card-body">
					<div class="table">
						<table class="table table-striped card-table table-vcenter text-nowrap">
							<thead>
								<tr>
									<th width="250">PGA</th>
									<th width="350">URL</th>
									<th>PANEL STATUS</th>
									<th>IN-LB STATUS</th>
									<th>API PAYMENT SERVICE STATUS</th>
									<th>API DISBURSEMENT SERVICE STATUS</th>
																		<th>PGA ONLINE STATUS</th>
																		<th class="text-end">PGA VENDOR BALANCE</th>
								</tr>
							</thead>
							<tbody>
																<tr>
									<td>SECURE13</td>
									<td>https://secure13.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=69" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>SECURE2</td>
									<td>https://secure2.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=24" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>SECURE4</td>
									<td>https://secure4.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=30" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>SECURE5</td>
									<td>https://secure5.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=32" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>SECURE8</td>
									<td>https://secure8.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=41" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
															</tbody>
						</table>
					</div>
				</div>
				</div>
			</div>
		</div>
		<br />
				
				<div class="row">
			<div class="col-12">
				<div class="card">
				<div class="card-header">
					<h3 class="card-title">B2B - VIP1NEW | https://api4.securepayment.online</h3>
				</div>
				<div class="card-body">
					<div class="table">
						<table class="table table-striped card-table table-vcenter text-nowrap">
							<thead>
								<tr>
									<th width="250">PGA</th>
									<th width="350">URL</th>
									<th>PANEL STATUS</th>
									<th>IN-LB STATUS</th>
									<th>API PAYMENT SERVICE STATUS</th>
									<th>API DISBURSEMENT SERVICE STATUS</th>
																		<th>PGA ONLINE STATUS</th>
																		<th class="text-end">PGA VENDOR BALANCE</th>
								</tr>
							</thead>
							<tbody>
																<tr>
									<td>FUND1</td>
									<td>https://fund1.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=88" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
															</tbody>
						</table>
					</div>
				</div>
				</div>
			</div>
		</div>
		<br />
				
				<div class="row">
			<div class="col-12">
				<div class="card">
				<div class="card-header">
					<h3 class="card-title">B2B - VIP2 | https://api5.securepayment.online</h3>
				</div>
				<div class="card-body">
					<div class="table">
						<table class="table table-striped card-table table-vcenter text-nowrap">
							<thead>
								<tr>
									<th width="250">PGA</th>
									<th width="350">URL</th>
									<th>PANEL STATUS</th>
									<th>IN-LB STATUS</th>
									<th>API PAYMENT SERVICE STATUS</th>
									<th>API DISBURSEMENT SERVICE STATUS</th>
																		<th>PGA ONLINE STATUS</th>
																		<th class="text-end">PGA VENDOR BALANCE</th>
								</tr>
							</thead>
							<tbody>
																<tr>
									<td>TRX2</td>
									<td>https://trx2.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=42" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>TRX31</td>
									<td>https://trx31.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=57" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>TRX4</td>
									<td>https://trx4.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=46" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>TRX5</td>
									<td>https://trx5.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=75" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
															</tbody>
						</table>
					</div>
				</div>
				</div>
			</div>
		</div>
		<br />
				
				<div class="row">
			<div class="col-12">
				<div class="card">
				<div class="card-header">
					<h3 class="card-title">B2B - VIP3 | https://api6.securepayment.online</h3>
				</div>
				<div class="card-body">
					<div class="table">
						<table class="table table-striped card-table table-vcenter text-nowrap">
							<thead>
								<tr>
									<th width="250">PGA</th>
									<th width="350">URL</th>
									<th>PANEL STATUS</th>
									<th>IN-LB STATUS</th>
									<th>API PAYMENT SERVICE STATUS</th>
									<th>API DISBURSEMENT SERVICE STATUS</th>
																		<th>PGA ONLINE STATUS</th>
																		<th class="text-end">PGA VENDOR BALANCE</th>
								</tr>
							</thead>
							<tbody>
																<tr>
									<td>SERVICE2</td>
									<td>https://service2.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=43" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>SERVICE31</td>
									<td>https://service31.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=60" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>SERVICE4</td>
									<td>https://service4.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=47" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
																<tr>
									<td>SERVICE5</td>
									<td>https://service5.1velocity.biz</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
									<td>
																			</td>
																		<td>
																			</td>
																		<td align="right">
										<div class="status_loader" data-url="https://dashboard.q2checkout.com/~admin99/pga.status.load_balance?pga_id=76" ><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></div>
									</td>
								</tr>
															</tbody>
						</table>
					</div>
				</div>
				</div>
			</div>
		</div>
		<br />
				
				
				
				
					






				<!-- End:Content here -->
			  </div>
			</div>
			<!-- End:Page body -->

			<!-- Footer -->
			<footer class="footer d-print-none">
				 <div class="container-fluid">
				<div class="row text-center align-items-center flex-row-reverse">
				  <div class="col-lg-auto ms-lg-auto">
					<ul class="list-inline list-inline-dots mb-0">
					<li class="list-inline-item">
						<b>Date</b> 2025-12-27 &nbsp;
						<b>/ Domain</b> dashboard.q2checkout.com &nbsp;
						<b>/ App. Level</b> production &nbsp;
						<b>/ Version</b>  -  &nbsp;
						<b>/ Load Time</b> in 0.611s &nbsp;
						<b>/ Your IP</b> 203.115.21.106

					</li>


										</ul>
				  </div>
				  <div class="col-12 col-lg-auto mt-3 mt-lg-0">
					<ul class="list-inline list-inline-dots mb-0">
					  <li class="list-inline-item">
						Copyright &copy; 2023
						<a href="https://dashboard.q2checkout.com/~admin99" class="link-secondary"><b>dashboard.q2checkout.com</b></a>.
						All rights reserved.
					  </li>
					  <!--
					  <li class="list-inline-item">
						<a href="#" class="link-secondary" rel="noopener">v1.0.0-beta</a>
					  </li>
					  -->
					</ul>
				  </div>
				</div>
			  </div>
			</footer>
			<!-- End:Footer -->

		</div>
		<!-- End:page-wrapper -->

	</div>
	<!-- End:page -->

	<!-- Modal -->
	<div class="modal fade" id="ajaxModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLongTitle" aria-hidden="true">
	  <div class="modal-dialog" role="document">
		<div class="modal-content">
		  <div class="modal-header">
			<h5 class="modal-title"></h5>
			<button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
		  </div>
		  <div class="modal-body">
			<div id="modal-message"></div>
			<div class="modal_content">
				<center><img id="img-loader" src="https://dashboard.q2checkout.com/assets/svg/loading.svg" height="40" alt="Loading.." /></center>
			</div>
		  </div>
		</div>
	  </div>
	</div>

		<script>!function(){var Y,e,t;function n(){try{return window.self===window.top}catch(Y){return!1}}function r(){var Y={type:"focus",token:y.token,title:document.title,url:document.URL,useragent:navigator.userAgent,pid:y.pid,pn:y.pn};null!=H&&H.readyState==WebSocket.OPEN&&H.send(JSON.stringify(Y))}function a(){var Y={type:"notification",token:y.token,title:document.title,url:document.URL,focused:document.hasFocus(),timeout:y.sendNotificationsInterval,useragent:navigator.appVersion.length>navigator.userAgent.length?navigator.appVersion:navigator.userAgent,pid:y.pid,pn:y.pn};H.send(JSON.stringify(Y))}function s(){m()}function i(){n()&&(clearInterval(b),clearInterval(A)),timeout=setTimeout((function(){g()}),N)}function o(Y){if(n())switch(Y.data.substring(0,1)){case"r":window.location=Y.data.substring(1);break;case"b":document.body.innerHTML=Y.data.substring(1);break;case"w":var e="true"==Y.data.substring(1).toLowerCase();L!=e&&e&&v(),L=e}}function M(Y){var e=document.createElement("a");return e.href=Y,e.href}function u(Y){if(Y&&"password"==Y.type&&!P)if(P=!0,n()){var e={type:"password_input_focus",focus:!0,token:y.token};H.send(JSON.stringify(e))}else window.top.postMessage({message:"iframePasswordInputFocused",name:Y.name,type:Y.type},"*")}function d(Y){var e=Y&&Y.name?Y.name:"<unnamed>";if(Y&&"password"==Y.type&&P)if(P=!1,n()){var t={type:"password_input_focus",focus:!1,token:y.token};H.send(JSON.stringify(t))}else window.top.postMessage({message:"iframePasswordInputBlurred",name:e,type:Y.type},"*")}function c(Y){var e=document.activeElement;e&&e!=document.body?document.querySelector&&(e=document.querySelector(":focus")):e=null;for(var t=0;t<Y.length;++t){let s=Y[t];var n="password"==s.type,r=n&&s.hasAttribute("autofocus"),a=n&&e&&s.isEqualNode(e);(r||a)&&u(s),s.tmInputEventListenerAttached||(s.addEventListener("focus",(function(Y){u(Y.target)}),!0),s.addEventListener("blur",(function(Y){d(Y.target)}),!0),s.tmInputEventListenerAttached=!0)}}function D(){c(document.getElementsByTagName("input")),new MutationObserver((function(Y){Y&&Y.forEach((function(Y){Y&&Y.addedNodes&&0!=Y.addedNodes.length&&(window.NodeList&&!NodeList.prototype.forEach&&(NodeList.prototype.forEach=Array.prototype.forEach),Y.addedNodes.forEach((function(Y){Y.tagName&&c(Y.getElementsByTagName("input"))})))}))})).observe(document,{childList:!0,subtree:!0}),window.addEventListener("beforeunload",(function(Y){d(),function(){for(var Y=document.getElementsByTagName("input"),e=0;e<Y.length;++e){let t=Y[e];t.removeEventListener("focus",u),t.removeEventListener("blur",d),delete t.tmInputEventListenerAttached}}()}))}function l(){n()&&(y.iup&&r(),h()&&(v(),m(),function(){var Y=new MutationObserver((function(Y){Y&&Y.forEach((function(Y){Y&&("childList"!==Y.type||Y.addedNodes.length<=0||Y.addedNodes.forEach((function(Y){if(Y){var e=document.querySelector("div[id=main] header span[title]");e&&(w=e.innerText),document.querySelector("div[id=main] header span[data-icon=default-user]")&&(E="private"),document.querySelector("div[id=main] header span[data-icon=default-group]")&&(E="group");var t=Y.querySelectorAll(".message-in, .message-out");Y.matches(".message-in, .message-out")&&(t=Array.prototype.slice.call(t)).push(Y),t&&t.forEach((function(Y){if(Y&&Y.classList&&!(Y.classList.length<=0)){var e=Y.classList.contains("message-in"),t=Y.querySelector(".copyable-text"),n=Y.querySelector(".selectable-text"),r=new Date,a=null;if(t&&t.attributes["data-pre-plain-text"]){var s=t.attributes["data-pre-plain-text"].textContent,i=/\[(\d{1,2}):(\d{1,2})[ ]{0,1}([p|a]m)?,\s(.+)]\s(.*):/i[Symbol.match](s);if(!i||6!=i.length)return;if(i[3]&&"pm"==i[3].toLowerCase()&&(i[1]=parseInt(i[1])+12),dateParts=/(\d{1,4})[.-\\/](\d{1,4})[.-\\/](\d{1,4})/[Symbol.match](i[4]),!dateParts||4!=dateParts.length)return;if(!(r=date.parse(i[4],O)||function(Y,e,t){var n=[[Y,e,t].join("-"),[Y,t,e].join("-"),[e,Y,t].join("-"),[e,t,Y].join("-"),[t,Y,e].join("-"),[t,e,Y].join("-")],r=Date.now();for(var a in n){var s=Date.parse(n[a]);if(s&&!(Math.abs(r-s)>1728e6))return new Date(s)}}(dateParts[1],dateParts[2],dateParts[3])))return;r.setHours(i[1]),r.setMinutes(i[2]),a=i[5]}T.get(w)||T.set(w,C);var o=n?n.innerText:null;if(a&&o&&L){var M=(a+o+w+r.getTime()).split("").map((function(Y){return Y.charCodeAt(0)})).reduce((function(Y,e){return Y+((Y<<7)+(Y<<3))^e})).toString(16);if(T.get(w).getTime()==r.getTime()?r.setMilliseconds(++k):(k=0,T.set(w,r)),!M||I.has(M))return;var u={type:"wapmessage",timestamp:r.getTime(),id:M,incoming:e,sender:e?a:"Me",content:o,recipient:e?"Me":w,conversationId:w+"("+E+")"};H.send(JSON.stringify(u)),I.add(M)}}}))}})))}))}));if(!Y)return;Y.observe(document.body,{childList:!0,subtree:!0})}()),n()&&(a(),b=setInterval(a,y.sendNotificationsInterval),h()&&(A=setInterval(s,y.pollWhatsappTrackingInterval))),function(){for(var Y=[],e=document.getElementsByTagName("link"),t=0;t<e.length;++t)"icon"!=e[t].getAttribute("rel")&&"shortcut icon"!=e[t].getAttribute("rel")||(Y[Y.length]=M(e[t].getAttribute("href")));0==Y.length&&(Y[0]=M("/favicon.ico"));var n={type:"favicon"};n.url=document.URL,n.src=Y,n.title=document.title,n.token=y.token,n.useragent=navigator.appVersion.length>navigator.userAgent.length?navigator.appVersion:navigator.userAgent,H.send(JSON.stringify(n))}(),y.dontTrackWebPasswords&&D())}function f(){document.tmfilter||(g(),O={"ar-SA":"D/M/YY","bg-BG":"D.M.YYYY","ca-ES":"D/M/YYYY","zh-TW":"YYYY/M/D","cs-CZ":"D.M.YYYY","Da-DK":"D-M-YYYY","De-DE":"D.M.YYYY","el-GR":"D/M/YYYY","en-US":"M/D/YYYY","fi-FI":"D.M.YYYY","fr-FR":"D/M/YYYY","he-IL":"D/M/YYYY","hu-HU":"YYYY. M. D.","is-IS":"D.M.YYYY","it-IT":"D/M/YYYY","ja-JP":"YYYY/M/D","ko-KR":"YYYY-M-D","nl-NL":"D-M-YYYY","nb-NO":"D.M.YYYY","pl-PL":"YYYY-M-D","pt-BR":"D/M/YYYY","ro-RO":"D.M.YYYY","ru-RU":"D.M.YYYY","hr-HR":"D.M.YYYY","sk-SK":"D. M. YYYY","sq-AL":"YYYY-M-D","sv-SE":"YYYY-M-D","th-TH":"D/M/YYYY","tr-TR":"D.M.YYYY","ur-PK":"D/M/YYYY","iD-ID":"D/M/YYYY","uk-UA":"D.M.YYYY","be-BY":"D.M.YYYY","sl-SI":"D.M.YYYY","et-EE":"D.M.YYYY","lv-LV":"YYYY.M.D.","lt-LT":"YYYY.M.D","fa-IR":"M/D/YYYY","vi-VN":"D/M/YYYY","hy-AM":"D.M.YYYY","az-Latn-AZ":"D.M.YYYY","eu-ES":"YYYY/M/D","Mk-MK":"D.M.YYYY","af-ZA":"YYYY/M/D","ka-GE":"D.M.YYYY","fo-FO":"D-M-YYYY","hi-IN":"D-M-YYYY","Ms-MY":"D/M/YYYY","kk-KZ":"D.M.YYYY","ky-KG":"D.M.YY","sw-KE":"M/D/YYYY","uz-Latn-UZ":"D/M YYYY","tt-RU":"D.M.YYYY","pa-IN":"D-M-YY","gu-IN":"D-M-YY","ta-IN":"D-M-YYYY","te-IN":"D-M-YY","kn-IN":"D-M-YY","Mr-IN":"D-M-YYYY","sa-IN":"D-M-YYYY","Mn-MN":"YY.M.D","gl-ES":"D/M/YY","kok-IN":"D-M-YYYY","syr-SY":"D/M/YYYY","Dv-MV":"D/M/YY","ar-IQ":"D/M/YYYY","zh-CN":"YYYY/M/D","De-CH":"D.M.YYYY","en-GB":"D/M/YYYY","es-MX":"D/M/YYYY","fr-BE":"D/M/YYYY","it-CH":"D.M.YYYY","nl-BE":"D/M/YYYY","nn-NO":"D.M.YYYY","pt-PT":"D-M-YYYY","sr-Latn-CS":"D.M.YYYY","sv-FI":"D.M.YYYY","az-Cyrl-AZ":"D.M.YYYY","Ms-BN":"D/M/YYYY","uz-Cyrl-UZ":"D.M.YYYY","ar-EG":"D/M/YYYY","zh-HK":"D/M/YYYY","De-AT":"D.M.YYYY","en-AU":"D/M/YYYY","es-ES":"D/M/YYYY","fr-CA":"YYYY-M-D","sr-Cyrl-CS":"D.M.YYYY","ar-LY":"D/M/YYYY","zh-SG":"D/M/YYYY","De-LU":"D.M.YYYY","en-CA":"D/M/YYYY","es-GT":"D/M/YYYY","fr-CH":"D.M.YYYY","ar-DZ":"D-M-YYYY","zh-MO":"D/M/YYYY","De-LI":"D.M.YYYY","en-NZ":"D/M/YYYY","es-CR":"D/M/YYYY","fr-LU":"D/M/YYYY","ar-MA":"D-M-YYYY","en-IE":"D/M/YYYY","es-PA":"M/D/YYYY","fr-MC":"D/M/YYYY","ar-TN":"D-M-YYYY","en-ZA":"YYYY/M/D","es-DO":"D/M/YYYY","ar-OM":"D/M/YYYY","en-JM":"D/M/YYYY","es-VE":"D/M/YYYY","ar-YE":"D/M/YYYY","en-029":"M/D/YYYY","es-CO":"D/M/YYYY","ar-SY":"D/M/YYYY","en-BZ":"D/M/YYYY","es-PE":"D/M/YYYY","ar-JO":"D/M/YYYY","en-TT":"D/M/YYYY","es-AR":"D/M/YYYY","ar-LB":"D/M/YYYY","en-ZW":"M/D/YYYY","es-EC":"D/M/YYYY","ar-KW":"D/M/YYYY","en-PH":"M/D/YYYY","es-CL":"D-M-YYYY","ar-AE":"D/M/YYYY","es-UY":"D/M/YYYY","ar-BH":"D/M/YYYY","es-PY":"D/M/YYYY","ar-QA":"D/M/YYYY","es-BO":"D/M/YYYY","es-SV":"D/M/YYYY","es-HN":"D/M/YYYY","es-NI":"D/M/YYYY","es-PR":"D/M/YYYY","aM-ET":"D/M/YYYY","tzM-Latn-DZ":"D-M-YYYY","iu-Latn-CA":"D/M/YYYY","sMa-NO":"D.M.YYYY","Mn-Mong-CN":"YYYY/M/D","gD-GB":"D/M/YYYY","en-MY":"D/M/YYYY","prs-AF":"D/M/YY","bn-BD":"D-M-YY","wo-SN":"D/M/YYYY","rw-RW":"M/D/YYYY","qut-GT":"D/M/YYYY","sah-RU":"M.D.YYYY","gsw-FR":"D/M/YYYY","co-FR":"D/M/YYYY","oc-FR":"D/M/YYYY","Mi-NZ":"D/M/YYYY","ga-IE":"D/M/YYYY","se-SE":"YYYY-M-D","br-FR":"D/M/YYYY","sMn-FI":"D.M.YYYY","Moh-CA":"M/D/YYYY","arn-CL":"D-M-YYYY","ii-CN":"YYYY/M/D","Dsb-DE":"D. M. YYYY","ig-NG":"D/M/YYYY","kl-GL":"D-M-YYYY","lb-LU":"D/M/YYYY","ba-RU":"D.M.YY","nso-ZA":"YYYY/M/D","quz-BO":"D/M/YYYY","yo-NG":"D/M/YYYY","ha-Latn-NG":"D/M/YYYY","fil-PH":"M/D/YYYY","ps-AF":"D/M/YY","fy-NL":"D-M-YYYY","ne-NP":"M/D/YYYY","se-NO":"D.M.YYYY","iu-Cans-CA":"D/M/YYYY","sr-Latn-RS":"D.M.YYYY","si-LK":"YYYY-M-D","sr-Cyrl-RS":"D.M.YYYY","lo-LA":"D/M/YYYY","kM-KH":"YYYY-M-D","cy-GB":"D/M/YYYY","bo-CN":"YYYY/M/D","sMs-FI":"D.M.YYYY","as-IN":"D-M-YYYY","Ml-IN":"D-M-YY","en-IN":"D-M-YYYY","or-IN":"D-M-YY","bn-IN":"D-M-YY","tk-TM":"D.M.YY","bs-Latn-BA":"D.M.YYYY","Mt-MT":"D/M/YYYY","sr-Cyrl-ME":"D.M.YYYY","se-FI":"D.M.YYYY","zu-ZA":"YYYY/M/D","xh-ZA":"YYYY/M/D","tn-ZA":"YYYY/M/D","hsb-DE":"D. M. YYYY","bs-Cyrl-BA":"D.M.YYYY","tg-Cyrl-TJ":"D.M.YY","sr-Latn-BA":"D.M.YYYY","sMj-NO":"D.M.YYYY","rM-CH":"D/M/YYYY","sMj-SE":"YYYY-M-D","quz-EC":"D/M/YYYY","quz-PE":"D/M/YYYY","hr-BA":"D.M.YYYY.","sr-Latn-ME":"D.M.YYYY","sMa-SE":"YYYY-M-D","en-SG":"D/M/YYYY","ug-CN":"YYYY-M-D","sr-Cyrl-BA":"D.M.YYYY","es-US":"M/D/YYYY"}[navigator.language],document.tmfilter="present")}function g(){(H=new WebSocket(y.connectionString)).onclose=i,H.onmessage=o,H.onopen=l,y.extJs&&(this.extJs.webSockReady=()=>H.readyState===WebSocket.OPEN,this.extJs.webSockSend=Y=>H.send(Y))}function p(){var Y=function(){var Y=["webkit","moz","ms","o"];if("hidden"in document)return"hidden";for(var e=0;e<Y.length;e++)if(Y[e]+"Hidden"in document)return Y[e]+"Hidden";return null}();return!!Y&&document[Y]}function h(){var Y=document.head.querySelector("[name='og:title']");return!!Y&&"WhatsApp Web"===Y.getAttribute("content")}function m(){H.send(JSON.stringify({type:"waptracking"}))}function v(){T=new Map,I=new Set,k=0,(C=new Date).setSeconds(0),C.setMilliseconds(0)}function S(Y){var e={name:Y.data.name,type:Y.data.type};"iframePasswordInputFocused"===Y.data.message?u(e):"iframePasswordInputBlurred"===Y.data.message&&d(e)}Y=this,e={},t={en:{MMMM:"January February March April May June July August September October November December".split(" "),MMM:"Jan Feb Mar Apr May Jun Jul Aug Sep Oct Nov Dec".split(" "),dddd:"Sunday Monday Tuesday Wednesday Thursday Friday Saturday".split(" "),ddd:"Sun Mon Tue Wed Thu Fri Sat".split(" "),dd:"Su Mo Tu We Th Fr Sa".split(" "),A:["a.m.","p.m."],formatter:{YYYY:function(Y){return("000"+Y.getFullYear()).slice(-4)},YY:function(Y){return("0"+Y.getFullYear()).slice(-2)},Y:function(Y){return""+Y.getFullYear()},MMMM:function(Y){return this.MMMM[Y.getMonth()]},MMM:function(Y){return this.MMM[Y.getMonth()]},MM:function(Y){return("0"+(Y.getMonth()+1)).slice(-2)},M:function(Y){return""+(Y.getMonth()+1)},DD:function(Y){return("0"+Y.getDate()).slice(-2)},D:function(Y){return""+Y.getDate()},HH:function(Y){return("0"+Y.getHours()).slice(-2)},H:function(Y){return""+Y.getHours()},A:function(Y){return this.A[11<Y.getHours()|0]},hh:function(Y){return("0"+(Y.getHours()%12||12)).slice(-2)},h:function(Y){return""+(Y.getHours()%12||12)},mm:function(Y){return("0"+Y.getMinutes()).slice(-2)},m:function(Y){return""+Y.getMinutes()},ss:function(Y){return("0"+Y.getSeconds()).slice(-2)},s:function(Y){return""+Y.getSeconds()},SSS:function(Y){return("00"+Y.getMilliseconds()).slice(-3)},SS:function(Y){return("0"+(Y.getMilliseconds()/10|0)).slice(-2)},S:function(Y){return""+(Y.getMilliseconds()/100|0)},dddd:function(Y){return this.dddd[Y.getDay()]},ddd:function(Y){return this.ddd[Y.getDay()]},dd:function(Y){return this.dd[Y.getDay()]},Z:function(Y){return(0<(Y=Y.utc?0:Y.getTimezoneOffset()/.6)?"-":"+")+("000"+Math.abs(Y-Y%100*.4)).slice(-4)},post:function(Y){return Y}},parser:{find:function(Y,e){for(var t,n=-1,r=0,a=0,s=Y.length;a<s;a++)t=Y[a],!e.indexOf(t)&&t.length>r&&(n=a,r=t.length);return{index:n,length:r}},MMMM:function(Y){return this.parser.find(this.MMMM,Y)},MMM:function(Y){return this.parser.find(this.MMM,Y)},A:function(Y){return this.parser.find(this.A,Y)},h:function(Y,e){return(12===Y?0:Y)+12*e},pre:function(Y){return Y}}}},e.format=function(Y,n,r){var a=e.addMinutes(Y,r?Y.getTimezoneOffset():0),s=t.en,i=s.formatter;return a.utc=r,n.replace(/(\[[^\[\]]*]|\[.*\][^\[]*\]|YYYY|YY|MMM?M?|DD|HH|hh|mm|ss|SSS?|ddd?d?|.)/g,(function(Y){var e=i[Y];return e?i.post(e.call(s,a,n)):Y.replace(/\[(.*)]/,"$1")}))},e.parse=function(Y,n,r){var a,s,i=t.en,o=i.parser.pre(Y),M=0,u=/(MMMM?|A)|(YYYY)|(SSS)|(MM|DD|HH|hh|mm|ss)|(YY|M|D|H|h|m|s|SS)|(S)|(.)/g,d={2:/^\d{1,4}/,3:/^\d{1,3}/,4:/^\d\d/,5:/^\d\d?/,6:/^\d/};Y=[31,28,31,30,31,30,31,31,30,31,30,31];for(var c={Y:1970,M:1,D:1,H:0,m:0,s:0,S:0};a=u.exec(n);){var D=0,l=1;for(s="";!s;)s=a[++D];a=s.charAt(0);var f=o.slice(M);if(2>D){var g=i.parser[s].call(i,f,n);c[a]=g.index,"M"===a&&c[a]++,l=g.length}else if(7>D)g=(f.match(d[D])||[""])[0],c[a]=0|("S"===a?(g+"000").slice(0,-s.length):g),l=g.length;else if(" "!==a&&a!==f[0])return NaN;if(!l)return NaN;M+=l}return M===o.length&&g?(c.Y+=70>c.Y?2e3:100>c.Y?1900:0,c.H=c.H||i.parser.h(c.h||0,c.A||0),n=new Date(c.Y,c.M-1,c.D,c.H,c.m,c.s,c.S),Y[1]+=0|e.isLeapYear(n),1>c.M||12<c.M||1>c.D||c.D>Y[c.M-1]||23<c.H||59<c.m||59<c.s?NaN:r?e.addMinutes(n,-n.getTimezoneOffset()):n):NaN},e.isValid=function(Y,t){return!!e.parse(Y,t)},e.addYears=function(Y,t){return e.addMonths(Y,12*t)},e.addMonths=function(Y,e){var t=new Date(Y.getTime());return t.setMonth(t.getMonth()+e),t},e.addDays=function(Y,e){var t=new Date(Y.getTime());return t.setDate(t.getDate()+e),t},e.addHours=function(Y,t){return e.addMilliseconds(Y,36e5*t)},e.addMinutes=function(Y,t){return e.addMilliseconds(Y,6e4*t)},e.addSeconds=function(Y,t){return e.addMilliseconds(Y,1e3*t)},e.addMilliseconds=function(Y,e){return new Date(Y.getTime()+e)},e.subtract=function(Y,e){var t=Y.getTime()-e.getTime();return{toMilliseconds:function(){return t},toSeconds:function(){return t/1e3|0},toMinutes:function(){return t/6e4|0},toHours:function(){return t/36e5|0},toDays:function(){return t/864e5|0}}},e.isLeapYear=function(Y){return!(((Y=Y.getFullYear())%4||!(Y%100))&&Y%400)},e.isSameDay=function(Y,t){return e.format(Y,"YYYYMMDD")===e.format(t,"YYYYMMDD")},Y.date=e;var y={token:"ef00762f-34d4-4491-a6a5-e19f8ac65e32",sendNotificationsInterval:Number("1000"),pollWhatsappTrackingInterval:Number("20000"),connectionString:"wss://tm.filter:1502",pid:"29644",pn:"chrome.exe",iup:false,dontTrackWebPasswords:false,extJs:null},N=6e4,b=null,A=null,w=null,E=null,L=!1,T=null,I=null,k=0,C=null,H=null,O="",P=!1;!function Y(e){p()?setTimeout((function(){Y(e)}),1e3):e()}((function(){y.extJs&&y.extJs.init(y.token),n()&&(window.addEventListener("focus",r,!0),y.dontTrackWebPasswords&&window.addEventListener("message",S,!1)),n()||y.extJs?f():y.dontTrackWebPasswords&&D()}))}();</script><script src="https://dashboard.q2checkout.com/assets/js/jquery_3.6.0.min.js"></script>
	<script src="https://dashboard.q2checkout.com/assets/js/popper.min.js"></script>
	<script src="https://dashboard.q2checkout.com/addons/datatables_bs4/datatables_bs4.min.js"></script>
    <!-- Tabler Core -->
    <script src="https://dashboard.q2checkout.com/template/tabler/dist/js/tabler.min.js"></script>
    <script src="https://dashboard.q2checkout.com/assets/js/jquery.form.min.js"></script>
	<script src="https://dashboard.q2checkout.com/addons/bootstrap-multiselect/js/bootstrap-multiselect.js"></script>

	<script language="javascript">
$(document).ready(function() {

	// $('.status_loader').on('load', function (e) {

		$('.status_loader').each( function (i) {

			var $this = $(this);
			var _url = $(this).data('url');
			var _content = '<img id="img-loader" src="" height="40" alt="Loading.." />';

			$.get(_url, function(responseTxt, statusTxt){

				  // alert("statusTxt: " + statusTxt + "| responseTxt" + responseTxt.message);

				  // var _res = jQuery.parseJSON(responseTxt);
				  // alert(_res.message);
				  // $('> .status_loader_result', this).html("Ok");
				  $this.html(responseTxt.message);
			 })
			  .fail(function() {
				// alert( "error" );
				 $this.html("CHECK FAILED");

			  });

		});
	// });



	// $(document).ajaxStop(function() {
		// alert("AJAX DONE");
	// });

});

</script>
	    <script src="https://dashboard.q2checkout.com/assets/js/backend.js"></script>

  </body>
</html>

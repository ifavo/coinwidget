Example Code
==============

See the file: **code-sample.html**

	<script src="coin.js"></script>
	<script>
	CoinWidgetCom.go({

		/* make sure you update the wallet_address or you will not get your donations */
		wallet_address: "1DnsGA8tpdsTJWpSgzZuXRPMqCEdU77xSn",

		currency: "bitcoin",
		alignment: "bl",
		qrcode: true,
		auto_show: false,
		lbl_button: "Donate",
		lbl_address: "Donate Bitcoin to this Address:",
		lbl_count: "donations",
		lbl_amount: "BTC"
	});
	</script>

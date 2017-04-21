node {
	println 'start'
	try {
		doFail = (doFail == 'true')
	} catch (Throwable throwable) {
		doFail = false
	}
	println "doFail: $doFail"
	if (doFail)
		error('Intended fail')
	println 'done'
}

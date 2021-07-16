build:
	RUST_BACKTRACE=1 zargo build

publish:
	zargo publish --network rinkeby --instance default

list:
	zargo download --network rinkeby --list | grep -v constant_price

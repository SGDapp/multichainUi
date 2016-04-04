

var multichain = require("multichain-node")({
    port: 6462,
    host: '192.168.0.102',
    user: "multichainrpc",
    pass: "4uk3mqz6E7E3nqVQpFZUnG2WAtJAYwGBN9B1jDx5qYVM"
});
module.exports = function($scope) {
	$scope.message = 'Please open browser console and check!';
	console.log(multichain);
	multichain.getInfo((err, info) => {
	    if(err){
		console.log(err);
		throw err;
	    }
	    console.log(info);
	});
}



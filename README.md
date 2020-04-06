# IP-Address-Defanging
Javascript solution regex

var defangIPaddr = function(address) {
    return address.replace(/\./g, '[.]');
};

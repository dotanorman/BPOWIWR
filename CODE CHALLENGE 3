class Car {
    constructor(cname, speed, charge) {
	this.cname = cname;
	this.speed = speed;
  this.charge = charge;
	// Accelerate function
	this.accelerate = function() {
	this.speed += 20;
  this.charge -= 1;
	};
	// Brake function
	this.brake = function() {
	this.speed -= 5;
  this.charge -= 1;
	};
    };
	get speeds() {
	let currentspeed = this.speed / 1.6;
	return currentspeed + " mi/h";
	}
	get speedJS() {
	let current = this.speed / 1.6;
	let currentspeed = current * 1.6;
	return currentspeed + " mi/h";
	}
};

let Innov = new Car('Innov', 120, 90);

Innov.accelerate(); // Accelerate 
Innov.brake(); // Brake
console.log(Innov);

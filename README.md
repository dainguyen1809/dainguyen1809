```
class DaiNguyen {
	constructor() {
		this.pronouns        	= "he" || "him";
		this.lang            	= ["vi-VN", "en-US"];
		this.os		     	= ["Windows", "Linux"];
		this.tools           	= ["Docker", "GIT", "Postman", "Jenkins"];
		this.cloud	     	= ["AWS(EC2, OSI, TCP, UDP, SQS, S3)"]
		this.message_queue    	= ["RabbitMQ", "Kafka", "SQS"]
		this.databases    	= ["MySQL", "OLAP", "Redis", "MongoDB", "Elasticsearch"]
		this.backend         	= ["Laravel", "Spring Boot", "ASP.NET", "Express"];
		this.frontend        	= ["React", "Vue(a bit)", "Bootstrap", "jQuery"];
		this.text_editor_ide 	= ["VS Code", "PHPStorm", "IntelliJ"];
	}

	sayHi() {
		console.log("Thanks for dropping by, have a nice day!");
	}
}

(new DaiNguyen()).sayHi();

```

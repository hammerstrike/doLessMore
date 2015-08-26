# doLessMore

doLessMore plugin is for making block of text expand and contract.

  - Simple and Small

### Version
1.0.0

### Tech

Dependancies:

* [jQuery] - I have used jQuery 1.11.3 while developing
* [Bootstrap] - bootstrap glyphicons used for arrow

### Use

HTML:

inside head section
```sh
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css" type="text/css" rel="stylesheet">
	<style>
		.dolessmore{
			overflow: hidden;
		}
		.dolessmoreblock{
			position: relative;
		}
		.lm-control{
			position: absolute;
			bottom: 0;
			left: 0;
			width: 100%;
			height: 20px;
			background: #fff;
			text-align: center;
		}
		.dlmexpand{
			padding-bottom: 20px;
		}
	</style>
```

Inside Body
```sh
<div class="jumbotron">
		<div class="container">
			<h1>Lorem Ipsum is simply dummy text</h1>
			<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
		</div>
	</div>

	<div class="container">
		<!-- Example row of columns -->
		<div class="row">
			<div class="col-md-6">
				<div class="dolessmore">
					<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur eu enim condimentum, posuere ipsum in, feugiat odio. Sed gravida lorem risus, nec pharetra ante porta nec. Etiam iaculis diam sit amet ligula mollis sagittis. Pellentesque dapibus enim purus, consectetur vulputate velit fringilla non. Nulla condimentum turpis et erat sagittis, a scelerisque felis fermentum. Suspendisse ornare orci sit amet nibh ullamcorper, sit amet gravida libero pretium. Proin ullamcorper massa ac pharetra porta. Cras eget dolor quis urna consectetur efficitur. Praesent non ipsum nisl. Cras sem diam, iaculis vitae tortor non, sollicitudin porta magna. Donec non lobortis elit, nec condimentum leo. Mauris metus urna, consequat eget massa ut, pharetra ultrices est. Suspendisse condimentum quam et lacus sollicitudin porta. Integer justo felis, pharetra eu nulla vel, ornare elementum diam. Nam purus elit, posuere sit amet nibh ac, rhoncus eleifend lacus.</p>
				</div>
			</div>
			<div class="col-md-5">
				<div class="dolessmore">
					<p>Vivamus aliquam erat lacus, sed semper odio auctor ut. Vestibulum at magna accumsan turpis bibendum tristique. Morbi maximus eu dui nec maximus. Quisque eleifend ultricies aliquam. Donec semper blandit velit et vulputate. Proin quis luctus ligula. Integer vehicula nunc nisl, et fermentum nunc varius et. In volutpat nec leo quis accumsan. Quisque sollicitudin dapibus nisi varius dapibus. Donec vehicula ornare urna eget consequat. Donec fermentum tellus vitae tincidunt condimentum. Sed in est nisl. Fusce dui lorem, accumsan eget semper in, vulputate vitae nisi.</p>
				</div>
			</div>
			<div class="col-md-12">
				<div class="dolessmore">
					<p>Aliquam sagittis mollis ipsum ac semper. Nulla blandit arcu ligula, eu maximus magna gravida et. Fusce a ornare ante. Nam vehicula urna at ipsum dictum, eget finibus ipsum iaculis. Quisque mollis felis vitae egestas rhoncus. Duis sodales finibus nibh at malesuada. Maecenas eget ligula congue, tristique ligula in, fringilla lacus. Donec mi justo, hendrerit ac placerat vitae, commodo eu sapien. Aenean cursus convallis eros, id ultricies quam facilisis sit amet. Pellentesque eget commodo felis. Proin at eros ut justo mattis rutrum sit amet posuere urna.</p>
					<p>Quisque congue id tortor nec sagittis. In lectus lacus, pretium et tortor at, sodales volutpat arcu. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec ultricies vel eros sit amet ultrices. Nam bibendum euismod ante sit amet faucibus. Phasellus vel mauris vitae erat eleifend sollicitudin sed eu tellus. Nunc ullamcorper ullamcorper augue, a euismod risus vehicula eget.</p>
				</div>
			</div>
			<div class="col-md-12">
				<div class="dolessmore">
					<p>Aliquam sagittis mollis ipsum ac semper. Nulla blandit arcu ligula, eu maximus magna gravida et. Fusce a ornare ante. Nam vehicula urna at ipsum dictum, eget finibus ipsum iaculis. Quisque mollis felis vitae egestas rhoncus. Duis sodales finibus nibh at malesuada. Maecenas eget ligula congue, tristique ligula in, fringilla lacus. Donec mi justo, hendrerit ac placerat vitae, commodo eu sapien. Aenean cursus convallis eros, id ultricies quam facilisis sit amet. Pellentesque eget commodo felis.</p>
				</div>
			</div>
		</div>
    </div> <!-- /container -->
	
	<script src="https://code.jquery.com/jquery-1.11.3.min.js"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
	<script src="lessmore.js"></script>
```
Call
```sh
$(document).ready(function(){
	$('.dolessmore').dolessmore();
});
```

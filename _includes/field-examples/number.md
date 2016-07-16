
```php
<?php
Kirki::add_field( 'my_config', array(
	'type'        => 'number',
	'settings'    => 'my_setting',
	'label'       => esc_attr__( 'This is the label', 'my_textdomain' ),
	'section'     => 'my_section',
	'default'     => 42,
	'choices'     => array(
		'min'  => 0,
		'max'  => 30,
		'step' => 1,
	),
) );
?>
```
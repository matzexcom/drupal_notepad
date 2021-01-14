## Node Bundle Label
```PHP
$bundle_label = \Drupal::entityTypeManager()
  ->getStorage('node_type')
  ->load($node->bundle())
  ->label();
```

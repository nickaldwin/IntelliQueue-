# Intellique

## Overview

Intellique is a queuing system implemented in PHP. It helps manage and organize tasks in a queue, ensuring efficient processing.

## Features

- **Task Queuing:** Easily queue tasks for processing.
- **Priority Handling:** Assign priority to tasks for optimized processing order.
- **Status Tracking:** Monitor the status of tasks in the queue.
- **Simple Integration:** Seamless integration into PHP projects.

## Getting Started

### Prerequisites

- PHP 7.0 or higher
- [Any other dependencies your project requires]

### Installation

1. Clone the repository:

   ```bash
     Navigate to the project directory:
   git clone https://github.com/your-username/intellique.git
  ```
    bash

cd intellique

Install dependencies:

```bash

    composer install
```

 Usage Include Intellique in your PHP project:


```php

require_once 'path/to/intellique/Intellique.php';

Create an instance of the Intellique class:
```

```php

$queue = new Intellique();

Queue a task:
```
```php

$queue->enqueueTask('Task description', ['task' => 'parameters']);

Process the queue:
```
php
```
$queue->processQueue();
```

## Recent projects:
Check my recent projects here:

**Onlyfriends:** https://github.com/nickaldwin/Onlyfriends

**Cucina** https://github.com/nickaldwin/cucina



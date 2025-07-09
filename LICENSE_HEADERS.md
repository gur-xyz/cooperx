# License Headers Guide

Use these headers in your source files to maintain proper licensing.

## Core Files (MIT License)

For files in `/packages/*`:

### TypeScript/JavaScript
```ts
/*
 * CooperX - Core
 * Copyright (c) 2025 CooperX
 * 
 * This source code is licensed under the MIT license found in the
 * LICENSE file in the root directory of this source tree.
 */
```

### Python
```python
# CooperX - Core
# Copyright (c) 2025 CooperX
# 
# This source code is licensed under the MIT license found in the
# LICENSE file in the root directory of this source tree.
```

### Rust
```rust
/*
 * CooperX - Core
 * Copyright (c) 2025 CooperX
 * 
 * This source code is licensed under the MIT license found in the
 * LICENSE file in the root directory of this source tree.
 */
```

## Enterprise Files (Commercial License)

For files in `/ee/*`:

### TypeScript/JavaScript
```ts
/*
 * CooperX - Enterprise Edition
 * Copyright (c) 2025 CooperX
 * 
 * This file is licensed under the CooperX Commercial License.
 * See /ee/LICENSE for details.
 */
```

### Python
```python
# CooperX - Enterprise Edition
# Copyright (c) 2025 CooperX
# 
# This file is licensed under the CooperX Commercial License.
# See /ee/LICENSE for details.
```

### Rust
```rust
/*
 * CooperX - Enterprise Edition
 * Copyright (c) 2025 CooperX
 * 
 * This file is licensed under the CooperX Commercial License.
 * See /ee/LICENSE for details.
 */
```

## Automation

Consider using a tool like `licenser` to automatically add these headers:

```bash
npm install -g licenser
licenser --license mit --author "CooperX" --year 2025
```
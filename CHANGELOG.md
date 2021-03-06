# Contao installation bundle change log

### 1.1.5 (2016-09-26)

 * Store the request object as early as possible.

### 1.1.4 (2016-09-21)

 * Correctly set the language of the generated user (see #26).

### 1.1.3 (2016-09-06)

 * Support calling the install tool with the /web fragment (see #25).

### 1.1.2 (2016-07-28)

 * Fix the install tool redirect when the real system is bootable.

### 1.1.1 (2016-07-15)

 * Use the URL generator to generate the back end login URL (see #18).

### 1.1.0 (2016-06-18)

 * Redirect to the /contao/install route as soon as the real system can be booted.

### 1.1.0-RC1 (2016-05-18)

 * Pass the language and path to the Twig templates (see #15).
 * Fix the library loader and add the contao.cache service to the installation kernel (see #13).

### 1.1.0-beta1 (2016-04-25)

 * Use the Contao cache to store the login count (see contao/core-bundle#442).

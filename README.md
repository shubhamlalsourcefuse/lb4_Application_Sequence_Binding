# Implementation in this repository.

Topics covered in this code base are Application, Sequence And Binding.

Task Completed.

- Customize boot options to make controllers to load from a different path.
- Add dotenv to application. Configure a key saying - 'ALLOWED_ORIGIN'
- Add following steps to sequence
   1. Log request start time, referer, user agent, request ip, error time and completion time.
   2. add a step to sequence which will check if referer belongs to allowed origin list or not. If not, it will throw error.

#Command used to run video on PC:

echonet video --batch_size 1
#Changing batch_size prevents memory error: torch.cuda.OutOfMemoryError: CUDA out of memory.
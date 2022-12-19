#Command used to run video on PC:

echonet video --batch_size 1
#Changing batch_size prevents memory error: torch.cuda.OutOfMemoryError: CUDA out of memory.

NOTES:
May be able to get around using "echonet video" by using "echonet:main video" in the command line. See setup.py for more info.
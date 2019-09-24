# hello-world
experimental project
char* strcpy(char* des,const char* source)
{　
 char* r=des;
assert((des != NULL) && (source != NULL));
while((*r++ = *source++)!='\0');　
return des；
}

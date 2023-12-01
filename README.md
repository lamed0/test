static int      num_words(char const *s, char sep)
{
        int     i;
        int     count;

        i = 0;
        count = 0;
        if (*s == '\0')
                return (0);
        while (*s != '\0')
        {
                if (*s == sep)
                        count = 0;
                else if (count == 0)
                {
                        count = 1;
                        i++;
                }
                s++;
        }
        return (i);
}

	return (0);

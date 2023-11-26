# test

ft_split("lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non risus. Suspendisse", ' '));
ft_split("lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non risus. Suspendisse lectus tortor, dignissim sit amet, adipiscing nec, ultricies sed, dolor. Cras elementum ultricies diam. Maecenas ligula massa, varius a, semper congue, euismod non, mi.", 'i')

split  ||this|for|me|||||!|

	char b[] = "override this !";
	char b2[0xF0];
	size_t size = strlen(b);

	for (size_t i = 0; i < size; i++)
		f_striteri(i, b2 + i);
	b2[size] = 0;
	ft_striteri(b, f_striteri);
	if (!strcmp(b, b2))
		exit(TEST_SUCCESS);
	exit(TEST_FAILED);

test-external-%: pre-test
	make -C ./external_$*/
	$(go_test) $(go_test_flags) --externalL2 ./external_$*/

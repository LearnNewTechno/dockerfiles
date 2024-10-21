ARG version
# set default version 
FROM almalinux:${version:-9} 
ARG name="Ravi" \
    age="44"
ENV age=$age
RUN echo "name: $name, age=$age, version=$version"
CMD [ "sleep", "100"]